# raspberry-pi-web-server
here i am figuring out how to use raspberry to host a web server remotely
### step1: downloading and activating ssh on ur native device
#### 2 ways to do so 
1)downloading openssh and activating it.<br>
the commands used r got from chagpt.  
[for open ssh](https://chatgpt.com/share/67c2e1d7-3aec-8007-9db2-8f6a4154ec73)

2)download putty app for ur respective os  
it's open source  
[putty](https://www.putty.org/)

### step2: to access of ur raspberry pi remotely via local network
so we have a few mini steps if u haven't set up ur raspberry pi  
since we're hosting a server i have gone with raspberry pi os lite  
u can u whatever u want depending on the neccesssity  

so first let's download a raspberry pi imager to load the os into ur ssd or sd card

[rpi imager](https://www.raspberrypi.com/software/)

![](https://github.com/user-attachments/assets/1387aab4-6d41-4990-99f8-0b075f17079f)

after downloading choose ur device here raspbery pi 5 
ur os i have selected lite and give next
![](https://github.com/user-attachments/assets/492ad5ed-9301-400d-9352-19a0ce368133)

after this customise ur setting by cicking edit settings
![](https://github.com/user-attachments/assets/0fae4be7-6481-477c-b4f8-473a05cd0b4c)

##### do enable ssh , its very important
![](https://github.com/user-attachments/assets/26eea602-21cb-4d83-b5e5-be04ea3a0bdf)

and start downloading the os in ur memory device

now u have downloaded ur os 
now to access ur open command prompt / powershell in administrator mode
find the ip of ur pi from the routers website now to connect with ssh
enter `ssh <ip of ur pi device>`
enter passwd if set 

and this shall be the final screen after set up
![](https://github.com/user-attachments/assets/70f6a02d-7fab-40ae-b494-613c3031dde1)

to know if pi is linked with the system use
enter `ping <pi's ip?>`


