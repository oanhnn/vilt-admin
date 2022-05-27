- [Setup MessageBird](#setup)
- [Send Message](#send)

# MessageBird
<br>
<img width="30%" src="data:image/png;base64,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" alt="messagebird logo"/>
<br>
Our framework support a <a href="https://www.messagebird.com/en/" target="_blank">MessageBird</a> SMS gate to send an SMS notifications to users or generate an OTP to auth the user form API
<hr>

<a name="setup">
## Setup MessageBird
</a>

to setup <a href="https://www.messagebird.com/en/" target="_blank">MessageBird</a> you need to go to website and register after that we can access developer area and get your api key

than go to route `/admin/services/messagebird`  and put your access key and your Originator phone number and Recipients name.

and you can access this data form a helper 

```php 
setting('messagebird.access_key')
```

```php 
setting('messagebird.originator')
```

```php 
setting('messagebird.recipients')
```
<hr>

<a name="setup">
## Send Message
</a>

to send a message with a MessageBird you can use our helper it make it very easy to send a message like this 
```php
send_sms(setting('messagebird.access_key'),setting('messagebird.originator'), $customerPhone, $customerMessage);
```
this helper take a value of access key and originator number and send a message to selected number with a selected message 