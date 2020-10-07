---


---

<h5 id="project-description">Project Description</h5>
<p>Project Idea</p>
<p>Maintaining attendance is very important in all the institutes for checking the attendance percentage of Students. Every institute has its own method in this regard. Some are taking attendance manually on the register for every hour and later they will upload every hour data of a class to the server or file-based approach and some have adopted methods of automatic attendance using some biometric techniques. But these methods are inefficient and time-consuming, AI can definitely find a solution to this problem.</p>
<p>Solution Requirements:</p>
<p>The proposed solution/application shall capture hourly attendance without any manual intervention. develop a smart device that can be integrated with a camera that will capture the images of class for every hour and send the images to model. Then the model will use AWS Rekognition Service to recognize the student’s faces &amp; push the images to S3(Simple Storage Service) for storage and also updates the attendance automatically in a database. build a web-based dashboard to visualize all the student’s attendance information.</p>
<p>Project Flow:</p>
<ul>
<li>
<p>Store the Images of Students in S3 Bucket</p>
</li>
<li>
<p>Capture the image on an Hourly basis</p>
</li>
<li>
<p>Load the image to Face comparison algorithm (compares the faces in s3 bucket)</p>
</li>
<li>
<p>Mark the attendance for compared faces and store in DynamoDb</p>
</li>
<li>
<p>Create a rest API using API gateway and lambda function to connect to dynamo DB through web app</p>
</li>
<li>
<p>Create a web-based dashboard to visualize the attendance</p>
</li>
</ul>
<p>Proposed Technical Architecture:</p>
<p><img src="https://lh5.googleusercontent.com/8OS3zIk4gVwVgBsFPew1dLHP0QvDpHt1lRqElwLkMvMmo4fJvqRHD0DWsRYo-wL_rlfSP-aA9GHSVEVz-_GQNZDg7umJm-alAHNrJKi-_yZT9vAAZgMjgrAoR2jeJBN_4CGZvPI" alt=""></p>

