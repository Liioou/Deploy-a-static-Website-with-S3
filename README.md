# Deploy a static Website with S3





<h2>Description</h2>
This project consist in deploying a static website with the target being a S3 bucket. User will be able to access it using the Dns name associated with our website. Making it simple for them to connect to it.
<br />
<br />
<br />



<h2>Services Used </h2>

- <b>AWS Route 53</b>

- <b>AWS S3</b> 
<br />



<h2>Program walk-through:</h2>

<p align="center">

 <br />

- <b> On S3 create the bucket (Name must match the domaine name that will be used for this project) <br/>
<br />
<br />

- <b> Uncheck "block public access" to make bucket public so that users can have access to the contain of the bucket
<br />
<br />


- <b> Once bucket is created, upload "index.html" file


<img src="https://i.imgur.com/8sYqRJh.png" height="80%" width="80%" alt="Create static website steps"/>
</p>
<br />
<br />




- <b> Under "Properties", scroll all the way down and enable hosting a static website
<br />
<br />



- <b> In the same setting where it says "Index document", put the name of the index.html file that was just uploaded and save changes


<img src="https://i.imgur.com/ptszXKq.png" height="80%" width="80%" alt="Create static website steps"/>
<br />
<br />



- <b> Under "Permission", edit the s3 policy bucket to give permission/access to bucket
<br />
<br />


- <b> Bucket should now be public:



<img src="https://i.imgur.com/yZTe3Oi.png" height="80%" width="80%" alt="Create static website steps"/>
<br />
<br />



- <b> On route 53 purchase the domain name of the website you are trying to create 
<br />
<br />


- <b> < Or if already have a registered domaine make sure subdomain match the bucket name you are using to create the static website >
<br />
<br />




- <b> Next create a record and select Alias. choose "Alias to S3 website endpoint" and select the region associated to the bucket:

<img src="https://i.imgur.com/PHVWWr6.png" height="80%" width="80%" alt="Create static website steps"/>
<br />
<br />


- <b> Test it:



<img src="https://i.imgur.com/GGs7oET.png" height="80%" width="80%" alt="Create static website steps"/>
<br />
<br />



- <b> Create image of the instance and test it





<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
