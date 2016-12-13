# mailcatcher docker container build

MailCatcher runs a super simple SMTP server which catches any message sent to it to display in a web interface. Run mailcatcher, set your favourite app to deliver to smtp://127.0.0.1:1025 instead of your default SMTP server, then check out http://127.0.0.1:1080 to see the mail that's arrived so far.

# how to run


    docker run -p 1025:1025 -p 1080:1080 palo/mailcatcher


Now you should be able to see the mailcatcher on [http://localhost:1080](http://localhost:1080)


