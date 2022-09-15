<samp>

# [Free WhatsApp Message](https://pypi.org/project/heyoo/)

[![Made in Tanzania](https://img.shields.io/badge/made%20in-tanzania-008751.svg?style=flat-square)](https://github.com/Tanzania-Developers-Community/made-in-tanzania)

Free WhatsApp Messages API [UDICTI TCMS-CRDB BootCamp 2022](https://udicti.udsm.ac.tz/)


## Use Case

1. Sending OTPs, Short Messages
2. Sending Logging Info's
3. Monitoring Software Actions like 
4. Sending Anonymous Messages. to people


[**NOTE**]()

- [**Iniate Conversation**]() with [+255 754 503 886](https://wa.me/255754503886/) i.e Make sure the receiver's whatsapp account number has sent atleast one physical message to [+255 754 503 886](https://wa.me/255754503886/)
- Use less than **256 characters** in your message.


### API
[https://crdb.zipa.tech/zipa-message/receiver-phone/your-message](https://crdb.zipa.tech/zipa-message/255718017738/I%20have%20visited%20your%20github%20Mr%20Kalokola/)

### Install requirements
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
>>> link = "https://crdb.zipa.tech/zipa-message/{}/{}/".format(receiver_phone, my_message)
>>> link
... "https://crdb.zipa.tech/zipa-message/255718017738/Hello Friend, Your WhatsApp OTP token is 878778

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