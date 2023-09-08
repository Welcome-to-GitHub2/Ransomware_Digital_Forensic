# Ransomware_Digital_Forensic
Investigating a kidnapped cat

<h1>Digital Forensics</h1>

<h2>Description</h2>
Our cat, Gado, has been kidnapped. The kidnapper has sent us a document with their requests in MS Word Document format. We have converted the document to PDF format and extracted the image from the MS Word file for your convenience.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Bash shell</b> 
- <b>Bash Linux commands</b>
- <b>THM AttackBox</b>


<h2>Environments Used </h2>

- <b>TryHackMe Virtual Machine</b>

<h2>Program walk-through:</h2>

<p align="center">
Ransom letter : <br/>
<img src="https://imgur.com/8EvpGTz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Checking the list of the files in the directory /root/Rooms/introdigitalforensics  <br/>
<img src="https://imgur.com/WLSJkN4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
reading the file metadata to find the author <br/>
<img src="https://imgur.com/bEbkAan.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
reading all the Exchangeable Image File Format(EXIF) data embedded in this image<b>  <br/>
metadata target<br/> 
Camera model / Smartphone model<br/>
Date and time of image capture<br/>
GPS coordinates embedded in the image<br/>
<img src="https://imgur.com/aZpU5v0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/1aT5waE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

Searching GPS coordinates on google maps to find the street that kidnappers took the image<br/>
<img src="https://imgur.com/SJuNIv4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

CONCLUSION:<br/><br/>
The image was captured at Milk Street using a Canon EOS R6.<br/>
Date/Time Original-->       2022:02:25 13:37:33.42+03:00 <br/>
The Author of the pdf is: Ann Gree Sheperd

<br />
<br />



<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
