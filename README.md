## Ducky Wifi Stealer

### Configuration (Gmail)
Replace `SENDER EMAIL` with the email you wish to send from.

Replace `SENDER PASSWORD` with the password of the sender email.

Replace `RECIPIENT MAIL` with the email you wish to send to.

### Info
Please note that this script is configured for Gmail, and therefore uses SSL and port 587 for SMTP. It is possible to use other email providers, but be sure to use the correct configuration.

Also note that while this script leaves behind no files, **it is by no means stealthy**. Your recipient, sender, and password will be saved in the PS command history, files will be recoverable with forensics, and an email is obviously sent from the target computer.
