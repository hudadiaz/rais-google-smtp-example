# Rails Gmail SMTP Sample

This is a simple app that takes some input to send emails. Emails will be sent as `GMAIL_ACCOUNT`.

## Inputs

 - to (comma seperated) **required**
 - cc (comma seperated)
 - cc (comma seperated)
 - subject **required**
 - content **required**
 
## ENV Config

  Set these env to use the app:
  
  - `GMAIL_ACCOUNT`
  - `GMAIL_ACCOUNT_PASSWORD`
  
## Google Settings

Because Google cares about security, the app wont be able to send email out of the box. *bummer*

### What to do

Based on this [question](http://stackoverflow.com/a/20262500) on SO, you need to visit this link:

[Allow access to your Google account](http://www.google.com/accounts/DisplayUnlockCaptcha)

If that is not enough, go to Google Security page, and toggle [Allow less secure apps](https://myaccount.google.com/security#connectedapps) to ON.

note: **these changes musy be made on the account you set as `GMAIL_ACCOUNT`**
