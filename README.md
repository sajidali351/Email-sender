# Python Email Sender
Python Email Sender
The Python email sender gives simplified acess to Python's built-in module for sending email over SMTP servers. The current version of the Python email sender supports plaintext and HTML style messages. Sendmail only supports Python3.

## Features
* Simplifies Python's email libraries into one easy to use object
* Send email messages in plain text or HTML markup
* Connects to SMTP servers using TLS or SSL

Notable missing features:

* Attachments are not supported yet
* Does not support setting recipients as CC/BBC yet

## Recommended settings
Gmail/GoogleApps:

* Using SSL: smtp.gmail.com, port 465
* Using TLS: smtp.gmail.com, port 587
Note: These connections may be blocked if 'Access for less secure apps' is disabled in your Google Account settings

Outlook.com/Live/Hotmail

* Using TLS: smtp.live.com, port 587
