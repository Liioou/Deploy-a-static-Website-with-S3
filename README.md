# Deploy a static Website with S3



 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2>Description</h2>
This project consist in deploying a static website with the target being a S3 bucket. User will be able to access it using the Dns name associated with our website. Making it simple for them to connect to it.

<br />

<h2>Environments Used </h2>

- <b>AWS Console</b>


<h2>Services and utility Used</h2>

- <b>Route 53</b> 
- <b>S3</b>




<h2>Program walk-through:</h2>




- Log into your Route 53 and register a domaine. This domaine will be used by our users to connect to your website.
- Create a bucket in s3. You want your bucket name to match the name you will be used for your website (example: s3.domainename.com)
- Make sure to uncheck the Block all public access to make sure users can have acess to your bucket
- Next go into your bucket and upload your <index.html> file
- Go to properties setting and At the bottom enable static website
- Under "Index document" is where you will add your <index.html> file and save changes
- Next go to Permissions and attach a bucket policy







<p align="center">
Launch the utility: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
