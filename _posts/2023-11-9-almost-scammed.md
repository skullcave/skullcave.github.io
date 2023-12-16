---
layout: post
title: "How I Was Almost Scammed"
description: "Discussing the time I was almost scammed and how to identify misleading emails."
author: "Sebastien Arseneault"
date: 2023-11-9
---

<style>
  .indented-text {
    margin-left: 30px;
    margin-right: 30px;
    font-size: 18px;
    color: white;
  }

  .underline {
    text-decoration: underline;
  }

  .post-image-container {
    text-align: center; /* Center the image within its container */
    margin-top: 20px; /* Add margin at the top for space */
    margin-bottom: 20px; /* Add margin at the bottom for space */
  }

  .post-image {
    max-width: 100%; /* Ensure the image doesn't exceed its container width */
    height: auto; /* Maintain aspect ratio */
    display: block; /* Center the image within its container */
    margin: 0 auto; /* Add margin to center the image */
    object-fit: cover; /* Maintain aspect ratio and cover the container */
  }

  @media (max-width: 600px) {
    .indented-text {
      margin-right: 10px; /* Adjust the right margin for smaller screens */
    }
  }
</style>

<h2 style="text-align: center; font-size: 20px;">How I Was Almost Scammed</h2>

<div class="indented-text">
  <i>December 27th, 2023</i><br><br>
  <i class="underline">Topics Discussed:</i> Phishing, Social Engineering, and OSINT.<br><br>
  
  For my first post, I will discuss the time I was almost scammed and we will also look at how to identify misleading emails.<br><br>
  
First, let's talk about how I found myself in this position and how I responded to it. On October 7th, 2023, I was emailed by an "HR Team" member with the company 'Avalon Flooring' about a job position titled Network Administrator. I thought great! I was in the process of applying for IT / Cybersecurity related jobs, and I sent out many applications during this period. The initial e-mail seemed legit from the outset; it had a solid sounding e-mail name 'edward@avalonflooringrecruit.com' and had a company logo in the signature. Being the expert that I am in this industry <em>&#42;sarcasm&#42;</em> I should have caught this. Below is a screenshot of the first e-mail that reeled me in:
  
  <div class="post-image-container">
    <img class="post-image" src="/assets/posts/scam-one.png" alt="first screenshot of scam">
  </div>

In the red rectangles you will see both the e-mail name and the signature of the e-mail. At a quick glance this all seems normal but upon further inspection something seems fishy. It simply states "HR Team". Typically, employees of companies will list their position title along with what department they work in within the company. If I had caught this sooner, it might have raised some alarm bells in my head. Regardless, let’s see how this e-mail chain progresses:

   <div class="post-image-container">
    <img class="post-image" src="/assets/posts/scam-two.png" alt="second screenshot of scam">
  </div>

This attachment was a PDF file that required you to fill out your name and then answer a series of questions pertaining to computer networking. In this same document it further stated the work schedule, benefits, and the pay range for this position. So of course, I answered the questions to the best of my knowledge I had relating to computer networking. Here was their response:

 <div class="post-image-container">
    <img class="post-image" src="/assets/posts/scam-three.png" alt="third screenshot of scam">
  </div>

The best part of this scam in my opinion was the wait. It took two days to hear back from the "recruiter" and this is what made me feel like this was legit. We have all been there, waiting on edge to see if we progressed in the hiring process, especially a remote job with lucrative pay. However, the content within this final e-mail is what raised the alarm.

<div class="post-image-container">
    <img class="post-image" src="/assets/posts/scam-four.png" alt="fourth screenshot of scam">
  </div>

In this fourth and final e-mail, I have highlighted the key indicators of this being a fraudulent job offer. First, 60 USD an hour is a high amount of money and in my experience amounts like these are usually discussed during virtual or in person interviews. Secondly, a user ID and password will be given to a new employee after 5 days?? This seems a little odd to me because there is usually an onboarding process when you sign an offer letter. During this process new employees will slowly earn username and passwords before being given full administrative control over systems. Thirdly and most importantly is the check they were going to send me. This is the most important part of the scam because this is how they profit. <br><br>

According to the FTC (2022) "in a fake check scam, a person you don’t know asks you to deposit a check". In the red rectangle we will see that this individual is asking for my full complete name, full mailing address, and further contact information such as my phone number. I believe that this information would have been used to generate a fake check that would then be mailed directly to me. At this point in the scam, the scammer will then ask for money back from the victim. Often the scammer will ask for this in the form of a gift card. <br><br>

At this point I began to do a little digging. Starting with the basics, I found Avalon Flooring USA on LinkedIn.

<div class="post-image-container">
    <img class="post-image" src="/assets/posts/avalon-flooring.png" alt="Avalon Flooring">
  </div>
  
From here I searched the employees list for “Edward Robinson", no luck. Then, I called their number to inform them about a potential scam going around that is using their name to support it. Next, I was connected with a helpful customer service representative, and she explained to me that this scam has been ongoing for a while.

<p style="text-align: center;"><strong><em>Key Takeaways</em></strong></p>

*References* 

FTC. (2022). How to spot, avoid, and report fake check scams.
  https://consumer.ftc.gov/articles/how-spot-avoid-report-fake-check-scams
  
</div>
