---


---

<h5 id="project-description">Project Description</h5>
<p>Project Idea:</p>
<p>Smart home applications with the Internet of things would be making some everyday tasks easier. Monitoring the room temperature will help the user in automating the appliances and make a better environment in the homes. Providing security is one of the key aspects and monitoring different hazards like gas leakage and fire detection will be helpful.</p>
<p>Solution Requirements:</p>
<p>In the proposed solution there will be live video streaming near the door which will detect the persons and capture their images. Whenever any person comes in front of the door it should alert the owner and send the image to his mobile app so that they can control the main door and give access to them. Store the images in Amazon S3. Monitor the room temperature, gas leakage, and fire detection using an online simulator by publishing data to AWS IoT core. Visualize the sensor data in the Mobile App.</p>
<p>Project Flow:</p>
<ul>
<li>
<p>Capture the image in the live video streaming when the face is detected using OpenCV.</p>
</li>
<li>
<p>Store the images in Amazon S3</p>
</li>
<li>
<p>Connect the online simulator sensor to AWS IoT core to publish temperature, gas level, and fire values.</p>
</li>
<li>
<p>Create the rules and actions in AWS IoT core to save the data in Dynamo DB.</p>
</li>
<li>
<p>Create an API using API Gateway and Lambda to retrieve the data from Dynamo DB</p>
</li>
<li>
<p>Create a mobile app to display the image from the S3 bucket and also to visualize the sensor parameters.</p>
</li>
</ul>
<p>Technical architecture:</p>
<p><img src="https://lh4.googleusercontent.com/ASQPISDW0yOSW5xsN6llS2zcKq4v9kt_2JYPN0-BlU0hFzg99FdtE3zpytJ_WLEMGM3DUP1TZbeZBVr_ZOwaBeRdWxEW7Ae_ARx9A6CBBacTJJKTeTtN2fN6qBLr64L7RRaanMM" alt=""></p>

