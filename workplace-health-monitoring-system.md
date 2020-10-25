
---

<h5 id="project-description">Project Description</h5>
<p>Project Idea</p>
<p>COVID-19 spread is emotionally challenging for many people, changing day-to-day life in unprecedented ways. All sections of society – including employers and employees, daily wage workers – should play a role to protect themselves and each other and help prevent further spread of the disease. WHO is providing advice and updated information on COVID-19, and on how employers can protect their employees, what measures they should take in the workplace, and other related factors. Even though the guidelines are issued it would become really a mess if any of the workers do not follow the guidelines</p>
<p>Solution Requirements:</p>
<p>The solution is to create a system that uses pre-installed cameras to analyze images from a construction site to see whether workers are adhering to safety measures, like wearing a helmet, maintaining social distancing, etc.</p>
<p>Project Flow:</p>
<ol>
<li>
<p>Use OpenCV for real-time capture of video and integrate AWS Recognition service to detect objects like a helmet, person, etc.,</p>
</li>
<li>
<p>Draw the bounding boxes around the detected objects using coordinates from AWS recognition response</p>
</li>
<li>
<p>If two persons are detected in a frame calculate the distance between two based on the coordinates</p>
</li>
<li>
<p>If the distance is less/ worker with no helmet, trigger voice over using Amazon Poly.</p>
</li>
</ol>
<p>Proposed Technical Architecture:</p>
<p><img src="https://lh6.googleusercontent.com/Y4UOVLDzPoru2atXu3b5gzwb6zCLaEbnyDqiP2Ae6Iu1xoO80FxJ4ENBnMBjbVtXhjFJvnQeGgN_ggKY68YYXk5dgQUgDD7GrHDBOmtnacn5HFpfXgbLFUu5GWl5yc8d9_XYIH8" alt=""></p>

