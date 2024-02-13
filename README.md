# change-psk-wlc
This script change the password of a wlc for any id regular and save the configuration to a tftp server

you can run the script with the following command

expect change_psk.exp wlc.txt

the wlc.txt should have the following format:

ip,hostname,wlan_id

for example:
--------------------------
10.61.2.133,hostname,2
.....
..
..

the password file:

passwords.txt

January,Bt4ever-01
February,Bt4ever-02
March,Bt4ever-03
April,Bt4ever-04
May,Bt4ever-05
June,Bt4ever-06
July,Bt4ever-07
August,Bt4ever-08
September,Bt4ever-09
October,Bt4ever-10
November,Bt4ever-11
December,Bt4ever-12

