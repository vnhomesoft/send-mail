# Demonstration Email Sending

Using MailKit and FakeSTMP

1. Start mail server
```
docker run -d -p 2525:25 -v /tmp/fakemail:/var/mail ghusta/fakesmtp:2.0
```

Reference: https://hub.docker.com/r/ghusta/fakesmtp

2. Run send mail program

3. Check sent mail
If using Linux, check email in mounted volumn `/tmp/fakemail`