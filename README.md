<samp>

# [Free WhatsApp Message](https://pypi.org/project/heyoo/)

[![Made in Tanzania](https://img.shields.io/badge/made%20in-tanzania-008751.svg?style=flat-square)](https://github.com/Tanzania-Developers-Community/made-in-tanzania)

Free WhatsApp Messages API [UDICTI TCMS-CRDB BootCamp 2022](https://udicti.udsm.ac.tz/)


## Use Case

1. Sending OTPs, Short Messages
2. Sending Logging Info's
3. Monitoring Software Actions like 
4. Sending Anonymous Messages. to people


NOTE: Use less than 256 characters


### API
[https://crdb.zipa.tech/<receiver-phone>/<your-message>/](https://crdb.zipa.tech/255718017738/I have visited your github Mr Kalokola/)

Example with OTPs
```bash
# install requests
$ pip3 install requests
# confirm if installed and see version
$ python3 -m  requests --version
```

### Exmaple on how to send WhatsApp OTP's
```python

## Check your versions on your terminal
>>> import requests

# define message requirements
>>> otp_token = 878778
>>> receiver_phone = "255718017738"

# view message
>>> my_message   = "Hello Friend, Your WhatsApp OTP token is {}".format(otp_token)
>>> my_message
... "Hello Friend, Your WhatsApp OTP token is 878778"

# view link
>>> link = "https://crdb.zipa.tech/{}/{}/".format(receiver_phone, my_message)
>>> link
... "https://crdb.zipa.tech/255718017738/Hello Friend, Your WhatsApp OTP token is 878778

# send your message
>>> response = requests.get(link)
>>> response
... {"success":True}
```

## All the credit

1. [Zipa Tech](https://github.com/zipa-tech)
2. [kalokola](https://github.com/kalokola)
3. Our Trainers & Coachs.
4. TCMS CRDB Class 2022.
</samp>