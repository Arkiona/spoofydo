# spoofydo
Ruby email spoofing script


```
Lightweight email spoofing scripts that uses a local SMTP server. 

ruby spoofy2.rb -h
Options:
  -u, --usage=<s>          ruby spoofy.rb -e email.html -s sender@email.com -n 'Sender Name' -t targets.txt -b 'Email Subject' 
  -e, --emailfile=<s>      HTML Template file
  -s, --senderemail=<s>    The sender email address
  -n, --sendername=<s>     The from name to be displayed in the email
  -t, --targets=<s>        The email address targets file
  -b, --subject=<s>        The subject
  -h, --help               Show this message



requires optimist gem. (gem install optimist)

requires a local SMTP server. Tested with postfix.
