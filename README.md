# Task1
In this task we are covering network basic understanding 

As we know network means connection between devices anytype of device 😅
and some people thing network and networking meaning is same but networking means to share or exchange information between devices in a network

Ok,Before going to scan ports
lets some gain knowledge of TCP
and UDP

In Simple words TCP (Transmission control protocol) which is a reliable connection oriented protocol means 
it first make connection and then
encrypts the traffic and then share or exchange any kind of files,info,data etc.
It used in applications and web technology.

UDP(User datagram protocol) which is a connection less and not a reliable protocol then why we use this because it is used for livestreams , games because if we make connection then we start the match it taks lot of time 🤣 


Lets talk about syn(synchronous) and ack(acknowledgement) flags

Think you want to propose a girl 😜 means you request for connection so it is syn flag and then girl say yes we make an relationship 😅 means it agree to make connection so it is ack flag
and when girl agree and request you to establish a realible 😄 relationship it means it is syn+ack and now you and your girl in realationship means connection is established.🎇

Lets think how can we find victim open ports means which services are open to all ?
Ans : Using nmap

for making an connection and find open ports use -sS flag means synchronous scan

nmap -sS (ip_range)
Ex : nmap -sS 192.168.29.0/24

If you want to save result in normal format use:
nmap -sS 192.168.29.0/24 -oN result

And if you are curious 🤨 to analyze packets then use wireshark and then select your interface like wlan0 and analyze packets 


Ok today is enough to learn.
Note : I writed whole writeup so sorry for grammer mistakes.
