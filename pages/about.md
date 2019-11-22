---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}**,<br>

I am a Experienced Software Developer with a demonstrated history of working in the information technology and services industry. I am a Seasoned Competative Programmer. I am skilled in Algorithms, C++, Python, Machine Learning and Event Management. I am a Strong information technology professional currently pursuing a Bachelor of Engineering - BE focused in Computer Science from Birla Institute of Technology and Science, Pilani.

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<p class="text-center">
{% include elements/button.html link="../assets/documents/Resume.pdf" text="Click here for my Resume" %}
</p>

<!-- <p class="text-center">
{% include elements/button.html link="mailto:singh.arshdeep1999@gmail.com" text="Please Contact on Email" %}
</p> -->

## **Contact Me!**

<form accept-charset="UTF-8" action="https://getform.io/f/497cc591-34d5-4259-a0f5-d5a46f0b5e1a" method="POST" enctype="multipart/form-data" target="_blank">
    <div class="form-group">
        <label for="exampleInputEmail1" required="required">Email address</label>
        <input type="email" name="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Enter email">
    </div>
    <div class="form-group">
        <label for="exampleInputName">Name</label>
        <input type="text" name="name" class="form-control" id="exampleInputName" placeholder="Enter your name" required="required">
    </div>
    <div class="form-group">
        <label for="exampleInputMessage">Your Message</label>
        <input type="textarea" name="message" class="form-control" id="exampleInputMessage" placeholder="Enter your message" required="required">
    </div>
    <button type="submit" class="btn btn-primary">Submit</button>
</form>