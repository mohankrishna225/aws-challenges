---


---

<h5 id="project-description">Project Description</h5>
<p>Project Idea</p>
<p>The project Intelligent water distribution system, as the name says it is all about management of water supply throughout the scale, right from small societies, townships to entire urban infrastructure and also for irrigation water supply management. The main task of the water distribution system is to maintain the water in the tank and also generate the water bills to the individual households which involve human efforts. This system can be automated using the Internet of things.</p>
<p>Solution Requirements:</p>
<p>The proposed system should continuously monitor the main tank water level and should automatically switch on/off the motors according to the tank water level and alert the <a href="http://admins.it">admins.it</a> should monitor the water flow of the individual houses and store the flow rate of each house in the DynamoDB to generate the water bills. The tank water level and the bills should be visualized in the Mobile App so that the Admin can monitor them. Alerts should be sent to Admin through SNS notification whenever the tank is full or empty.</p>
<p>Project Flow:</p>
<ul>
<li>
<p>Main tank water level and water flow to individual houses are continuously published to AWS IoT core (Use Online simulator sensor for water flow and water level)</p>
</li>
<li>
<p>Create a rule and actions in AWS IoT core to store the data in Amazon DynamoDB.</p>
</li>
<li>
<p>Create a rule and action in AWS IoT to send SNS when the tank level is full or empty.</p>
</li>
<li>
<p>Create an API using Amazon API gateway and lambda function to retrieve the data from DynamoDB.</p>
</li>
<li>
<p>Create the mobile app to display tank water level</p>
</li>
<li>
<p>Retrieve the flowrate of individual houses, generate bills, and display them in mobile App.</p>
</li>
</ul>
<p>Proposed Technical Architecture</p>
<p><img src="https://lh6.googleusercontent.com/2Itzg4njNOs28gj_WPV74spdfxhUWoib-cl4YgrXu7-6QZPJ7UXIGvCpqDtG5sf1HgJnm6e0Xckh-g0buWnsSnCdKBI_lfEE3mmBRsvHyMIHrHmoeEap9G1OIpp9SNkwoU8ZbTc" alt=""></p>

