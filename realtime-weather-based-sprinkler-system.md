---


---

<h5 id="project-description">Project Description</h5>
<p>Project Idea:</p>
<p>One of the major factors in the design, refurbishment, and long-term maintenance of any golf course is the way the greens and fairways are watered. In some golf courses watering systems such as sprinklers or drip water wires are fitted to sprinkle the water automatically and reduce human load. Normally sprinkler systems operate with respect to time, which means if we program it at 9 am it will be on even if rain occurs during that particular time. Since water is a precious resource we need to use it very carefully. The Internet of things will make the system more efficient.</p>
<p>Solution Requirements:</p>
<p>In the proposed solution the temperature, humidity, and soil moisture levels in the golf course should be continuously monitored, updated to AWS IoT Core, and store the data in dynamo <a href="http://DB.by">DB.by</a> considering the weather forecasting details from the open weather API the system should control the sprinklers automatically. Develop a mobile app to visualize the soil moisture and weather parameters.</p>
<p>Project Flow:</p>
<ul>
<li>
<p>Configure and connect the online simulator to publish temperature, humidity, and soil moisture values to AWS IoT core.</p>
</li>
<li>
<p>Create the rules and actions to store data in Dynamo DB</p>
</li>
<li>
<p>Create an API to retrieve the data from Dynamo DB using API Gateway and Amazon Lambda functions.</p>
</li>
<li>
<p>Create a mobile app to visualize the sensor parameters and also to get the open weather data.</p>
</li>
<li>
<p>Configure the mobile app to send commands to AWS IoT core to control the sprinklers based on the sensor values and weather details.</p>
</li>
</ul>
<p>Proposed Technical Architecture</p>
<p><img src="https://lh5.googleusercontent.com/YMhS47ItXFwdgDzGAe5z78dPEXvWDRzoCQ9vYmZ9-bhrwNdFT2iV7hgp2OvKDmMZbowVr22zIQRH2vteXZ2l3MTJpzHdAsTD-NIroWt8BzrYdnnLMHuX6PQHXBW5WgPyT02DacQ" alt=""></p>

