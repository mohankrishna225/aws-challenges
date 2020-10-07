---


---

<h5 id="project-description">Project Description</h5>
<p>Project Idea</p>
<p>In the current age, people are more conscious about their food and diet to avoid poor health. In order to properly assess dietary intake, an accurate estimation of the calorie value of food is of paramount importance. an application deployed on smartphones of users shall be capable of recognizing the food &amp; its calorie value so that users will track the number of calorie intake on a daily /weekly/monthly basis.</p>
<p>Solution Requirements:</p>
<p>This project aims at building a web App/android app which automatically recognizes food attributes such as ingredients and nutritional value by classifying the input image of food. Our method employs AWS Recognition service for accurate food classification and Food API’s to give the nutritional value of the identified food and save the calorie count in the database</p>
<ul>
<li>
<p>The user interacts with the mobile app, captures, and Loads an image.</p>
</li>
<li>
<p>The image is passed to the server application, which uses the AWS Rekognition service to analyze the images</p>
</li>
<li>
<p>Parse the output of analyzed image and get the nutrition content of the parsed output using Nutrition API,</p>
</li>
<li>
<p>Count the calories and save them in DynamoDB</p>
</li>
<li>
<p>Showcase the daily intake of calories on App UI(User Interface)</p>
</li>
<li>
<p>Nutritional information of the analyzed image is returned to the app for display.</p>
</li>
</ul>
<p>Proposed Technical Architecture:</p>
<p><img src="https://lh5.googleusercontent.com/2rYM3lrp1fWHwaInoYi0v2BD7XQPOKTeTvnblHMwy4RuDjS4TD5-Bg5V1PF7uJ7MKdFNiWW6zFklBuMEfMS2wKJ4XEt5oJSWqv2qB9TbUGVxO1yw7rxPFGnfNpK0ziA90BqQpqU" alt=""></p>

