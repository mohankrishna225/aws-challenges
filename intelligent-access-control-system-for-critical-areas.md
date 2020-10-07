---


---

<h5 id="project-description">Project Description</h5>
<p>Project Idea:</p>
<p>Industrial hazards may be defined as any condition produced by industries that may cause injury or death to personnel or loss of product or property. Safety in simple terms means freedom from the occurrence of risk or injury. Industrial safety refers to the protection of workers from the danger of industrial accidents. In some industries, it is necessary for the workers to take safety measures like helmet, shoes, gloves, etc. while working. So to check whether workers are taking safety precautions or not is the main task of the administration before the workers enter their working area which can be implemented using the Internet of things.</p>
<p>Solution Requirements:</p>
<p>The proposed system will be integrated near the entrance of the working area which will detect the person and check whether the person is wearing a safety helmet and shoes using Amazon Rekognition service. If the person is taking safety precautions the door should be opened or else it should generate the voice alerts why he can’t enter inside using Amazon Polly service. All the images should be stored in the Amazon S3 so that the admin can access the image. By face comparison techniques it should mark attendance to workers and store that in dynamo DB. Build a mobile app in which admin can access the attendance of that particular day.</p>
<p>Project Flow:</p>
<ul>
<li>
<p>Detect the face in the live video streaming and capture the image</p>
</li>
<li>
<p>Compare the captured image with the employee images in S3 and store the attendance in Dynamo DB.</p>
</li>
<li>
<p>In the captured image detect the helmet and shoes using Amazon Rekognition service</p>
</li>
<li>
<p>Store the images in the S3 bucket, images of the person taking safety precautions and not taking precautions should be separately stored</p>
</li>
<li>
<p>Create an API using API Gateway and Lambda function to retrieve the attendance from the Dynamo DB.</p>
</li>
</ul>
<p>Proposed Technical Architecture</p>
<p><img src="https://lh5.googleusercontent.com/Hi47HGCjQ8MzDti8-LYW1U-n9_5SedRkOB0gEyV-5-U6IETMI2zbo87zVxoo_EJ6nqbT5Eyu1UehdFdo0eejLQCk8NDNJhrM2RbHyBabhXYCHogVY7F4d8kLjsPFxjHHlCtFysA" alt=""></p>

