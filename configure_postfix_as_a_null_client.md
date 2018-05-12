#configure postfix as a null client
postconf - e "relayhost=[smtpX.example.com]"
postconf - e "inet_interfaces=loopback-only"

