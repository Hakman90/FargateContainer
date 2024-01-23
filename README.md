<h1>Deploying Container Using Fargate</h1>

<h2>Description</h2>
This project demonstrates how to create a docker image and deploy it using Fargate.
<br />

<h2>Project walk-through:</h2>

<p align="center">
Install Docker: <br/>
<img src="https://i.imgur.com/YghWPmv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Start Docker Service: <br/>
<img src="https://i.imgur.com/lSww0dt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
upload Docker file to the Instance and build Docker image from that file :  <br/>
<img src="https://i.imgur.com/ms0ff8K.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
upload image to Docker Hub :  <br/>
<img src="https://i.imgur.com/rCljT05.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create Fargate Cluster: <br/>
<img src="https://i.imgur.com/oqPSbaz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create a task definiton & link docker image :  <br/>
<img src="https://i.imgur.com/n6RAXbs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Run Fargate Task:  <br/>
<img src="https://i.imgur.com/V3mPXVs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Container Complete:  <br/>
<img src="https://i.imgur.com/4TkT5cy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
