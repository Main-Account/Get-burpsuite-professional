# Get-burpsuite-professional
hello, today I share with you the steps to crack &amp; Install Burpsuite Pro in Kali-Linux

![alt text](https://miro.medium.com/max/720/0*Q__Qg-YZ4DN_udMW)


What is Burpsuite?
Burp Suite is an integrated platform/graphical tool for performing security testing of web applications. Its various tools work seamlessly together to support the entire testing process, from initial mapping and analysis of an application’s attack surface, through to finding and exploiting security vulnerabilities.

Follow below steps to get the Professional version of BurpSuite.

Steps:
Download the Burp-Suite from the link: https://mega.nz/folder/9slnkTxR#aif6p6nWN8zNQgrNiiOixg

Extract the file. (Password: 123)

Visit the folder & Open terminal there
![alt text](https://miro.medium.com/max/640/1*kn2bwG94r7LkPL1jWUzgtg.webp)


Now run the following command to run the BURP-Loader:

java -jar burploader.jar
![alt text](https://miro.medium.com/max/720/1*4yxra1EkcNJL0hz-xjNeTg.webp)


Copy the License key and Press Run Button.

![alt text](https://miro.medium.com/max/720/1*EZ6PU0Ph1s54Ynh_sWkZPQ.webp)

Press I Accept to agreement.

![alt text](http://url/to/img.png)

Copy the key and Paste it into license field, and click next.
![alt text](http://url/to/img.png)


Now Press on “MANUAL ACTIVATION”
![alt text](http://url/to/img.png)


Now follow the steps in below image and copy paste the activation codes accordingly, and click next
![alt text](http://url/to/img.png)


Your Burpsuite Professional will be activated.

![alt text](http://url/to/img.png)

Now open Terminal into the same folder you extracted the BURPSUITE Zip file and type the below command

echo java -noverify -javaagent:burploader.jar -jar burpsuite_pro_v2020.12.1.jar > burp


Change the file permission by using the below command

chmod +x burp


Now move the file into the /bin folder, so you can run burpsuite professional.

mv burp /bin


Now just type “burp” into the terminal and the Burpsuite Professional will be launched.

burp
![alt text](http://url/to/img.png)
![alt text](http://url/to/img.png)


We have successfully cracked Burpsuite, Now Happy Hunting for Bugs :)

All credits to : 
https://systemweakness.com/how-to-crack-install-burpsuite-professional-in-kali-linux-a67eccba8b3d
