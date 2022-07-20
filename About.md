## Fiqsy (E-Scooters and Cars)
[Fiqsy](https://www.fiqsy.com/) is a E-Scooter and Car sharing service in Latvia.
For some reason they don't really care about their security and someone abusing their API's, so there is no limit on what you can do and how many API calls can you do before getting timeout. Great, right?
Bellow you can find some API Request templates and scripts usable with Fiqsy service.
## Request SMS OTP
Send a `POST` request to `https://0auth.fiqsy.com/oauth/vcode` with the following body in `FORM url encoded` format:
| Parameter |  Value|
|--|--|
| phone |  Phone number to send SMS to|
|  country_code| Country code of phone number used |
|  locale| Language for SMS *(en/lv/ru can be used)* |
