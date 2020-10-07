---


---

<h5 id="project-description">Project Description</h5>
<p>Project Idea:</p>
<p>Maintaining the parking slots and intimating the visitors about the empty slots is a major task in all the public places and shopping malls where there is a huge <a href="http://crowd.in">crowd.in</a> places where the security is most important aspect, the number of place detection plays a key role. Using IoT the parking system can be automated and help the users in minimizing their search time for the parking slots and also helps the authorities in some aspects of security.</p>
<p>Solution Requirements:</p>
<p>The proposed solution is to control the gates at the parking area automatically whenever a car is detected. Recognizing the number plate and storing the details in the DynamoDB which would be helpful for the authorities. The status of the parking slots should be monitored with the help of sensors. Near the gate, a speaker should be integrated which will give audio messages for the users to instruct them. Develop a mobile app through which the users can see the parking slots status and also for the authorities to the number plate details of all the vehicles on that particular day.</p>
<p>Project Flow:</p>
<ul>
<li>
<p>In the video streaming detect the vehicle, when the vehicle is detected capture the image and using amazon Rekognition service detect the number plate details</p>
</li>
<li>
<p>Publish these number plate details to AWS IoT Core and create rules, actions in AWS IoT core to store data in Dynamo DB.</p>
</li>
<li>
<p>Store the captured images in Amazon S3.</p>
</li>
<li>
<p>Generate the audio messages using Amazon Polly service to give instructions to the user.</p>
</li>
<li>
<p>Use the online simulator sensor and publish the sensor values to AWS IoT core to get the status of the parking slots.</p>
</li>
<li>
<p>Store the parking slot information in the Dynamo DB</p>
</li>
<li>
<p>Create an API to retrieve the data from Dynamo DB using API Gateway and Amazon Lambda.</p>
</li>
<li>
<p>Create a mobile app to visualize the parking Slot information and also the number plate details of that particular day.</p>
</li>
</ul>
<p>Proposed Technical Architecture:</p>
<p><img src="https://lh4.googleusercontent.com/M_eaBwffy0mcqCMWMnxG0yDtkPTR3LFNeOuBFgcf7SIjcMH6nWjidNPc1mUdtBVA__gjWfdPq-6DxglI0A2Fv3IJjw1DqhruH4nWbrTYemWJanqwxGwni3C9XJscrQkbexCbHjg" alt=""></p>

