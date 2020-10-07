---


---

<h5 id="project-description">Project Description</h5>
<p>Project Idea:</p>
<p>This application is intended to provide information about containment zones in a particular region by alerting people, through continuous monitoring of an individual’s location. The key benefits of the application are monitoring people’s activity and alerting for their safety movements.</p>
<p>Solution Requirement:<br>
The project aims at building an application that provides information about the containment zones of a particular region by continuously monitoring an individual’s location. The location of the individual must be stored in DynamoDB. Alerts are sent using the SNS service. The Application must be deployed using the Elastic Beanstalk. Create an API Endpoint for the model with the help of API Gateway and AWS Lambda Service.</p>
<p>Features of the Application</p>
<p>Admin App (portal):</p>
<p>They should have a login to the app and update the containment zones locations in the portal. Based on the location a Geofence will be created within a 100 meters radius. They should be able to see how many people are visiting that zone.</p>
<p>UserApp (Mobile App):</p>
<p>The app should have user registration and login. After the user logged into the app it will track the user location and update the database with the current location. If the user is visiting the containment zone he will get an alert notification</p>
<p>Proposed Technical Architecture:</p>
<p><img src="https://lh4.googleusercontent.com/ka6sB3YpDIirFV1Qo-X8YPRkIYiJp2E26iUY69GmxckLd02ej2xc9oCPHwbCEjXnwMQHP9Y4yjAN_XTZqIMwVzRe6ozZBXY1ahrlInlJg-pOxD7jzUQlOLvTAi-fAFi0G22Ox7s" alt=""></p>

