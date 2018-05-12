#configure postfix as a null client
postconf - e "relayhost=[smtpX.example.com]"
postconf - e "inet_interfaces=loopback-only"
systemctl restart postfix
hello
test
test coomit -a
