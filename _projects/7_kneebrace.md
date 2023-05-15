---
title: "Variable stiffness knee brace"
#excerpt: "Short description of portfolio item number 1<br/><img src='/images/Laser_scanner.png'>"
permalink: /project/kneebrace
collection: projects
header:
  teaser: "Teaser_knee_brace_300.png"
---
This project was conducted as the central component of an intensive medical device design course taught by Prof. Conor Walsh at Harvard (ES 227). Our team worked with a local clinician to develop a variable stiffness knee brace that provides support only when needed. The goal was to reduce non-contact ACL injuries by using a brace that provides stiffness only when injurious motions would be performed. In practice, this is a very difficult problem because of the serial compliance of human skin; it is difficult to achieve a stable mechanical ground onto which to anchor the brace.

A large portion of our efforts consisted of conducting benchtop tests using simulated leg models to understand the statics and kinematics implications of using bracing elements of varying material, number, and configuration.  

**Benchtop testing:** This video shows a combination of stiffening modules that activate protection at critical angles for tibial and valgus rotation that have been identified as risk thresholds for non-contact ACL injuries. It is also important that the stiffening modules have minimal effect on knee flexion:
{% include youtubePlayer.html id="juxn3izgLTM"%}

**Demonstration video:** This video demonstrates the variable-stiffness knee brace concept in action. A prototype brace was made by a functional apparel designer who was working with Prof. Walsh at the time. The video shows, in a somewhat over-the-top way, that our brace didn't impede motion. Further development and much broader testing would be needed to show an impact on ACL injury reduction:
{% include youtubePlayer.html id="gq6sDgWenPw"%}

\
**Experimental setup:** This shows the integrated test rig with force sensor, IMU, leg model, and data acquisition system:
<figure>
    <img src= "{{ "Knee_test_rig.JPG" | prepend: "/images/" | prepend: base_path }}"
         alt="Simulink model"
         style="width:100%">
</figure>

\
**Knee brace frame analysis:** This shows the coordinate frame analysis used to extract the knee rotation angles from the IMU during bracing simulations:
<figure>
    <img src= "{{ "Knee_frame_analysis.PNG" | prepend: "/images/" | prepend: base_path }}"
         alt="Simulink model"
         style="width:100%">
</figure>
