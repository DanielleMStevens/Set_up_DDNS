# Set_up_DDNS

To see networks and their IP addresses
```
ifconfig -a
```


Set up and Run no-ip
```
noip2 -C (create configuration) 
noip2 -S (see current running configurations)
noip2 -K ##### (kill current configuration)
```


if there are permssion issues with noip2 -C
```
sudo chmod a+rwx /usr/local/etc /usr/local/etc/no-ip2.conf
```
https://www.noip.com/support/knowledgebase/how-to-configure-ddns-in-router/
