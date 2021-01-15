---
title: "Centimeter-scale laser steering"
#excerpt: "Short description of portfolio item number 1<br/><img src='/images/Laser_scanner.png'>"
permalink: /project/cm_laser
collection: projects
header:
  teaser: "Teaser_cm_laser_72.png"
---

<figure>
    <img src= "{{ "Laser_Scanner.png" | prepend: "/images/" | prepend: base_path }}"
         alt="cm laser scanner"
         style="width:100%">
    <!-- <figcaption>Centimeter laser steering system</figcaption> -->
</figure>

I became interested in the use of lasers for minimally invasive surgery when learning about the way that lasers are used for vocal fold polyp resection in a procedure known as transoral laser microsurgery. The precision of the laser allows surgeons to make very fine dissections to retain healthy tissue and recover voice function. I then began investigating how the precision of that procedure could be brought into other surgical arenas such as laparoscopy and gastroenterology. Unfortunately, the laser used for vocal fold resection is highly specialized for that procedure; it is controlled by mirrors outside the patient's body and aimed through their airway down to the vocal folds. However, I realized that the laser steering elements could be miniaturized using the tools and techniques we have developed in the Wood Lab at Harvard. The idea is to put the laser steering components onto the ends of surgical tools, such as flexible colonoscopes and laparoscopic manipulators, with the ultimate aim of providing dramatically improved incision quality relative to existing static laser, electrocautery, and cold surgical tools.

This prototype was developed in collaboration with a visiting Master's student, Simon Bothner, from EPFL. Simon did the mechanical and optical design, I did the control, and we worked together on the fabrication. The basic idea is to mount miniature mirrors on flexible linkages that can be controlled with high-bandwidth piezoelectric bending actuators. We used a mixture of custom and off-the-shelf components, and a mixture of CNC and printed circuit MEMS fabrication techniques. The final design was 15 mm in diameter, 45 mm in length, and achieved an 18 x 10 mm range of motion at 20 mm standoff distance with mechanical bandwidth of 750 Hz.

**Principle of operation and system overview:** This video demonstrates the use of piezoelectric bending actuators to control the orientation of miniature mirrors:
{% include youtubePlayer.html id="QvrKOkfi4kk"%}


**Teleoperation:** This video shows the use of a Phantom Omni input device to control the position of the laser. A clutching scheme allows the user to maintain an ergonomic grip on the input device throughout the workspace of the laser. A large range of motion is achieved with low control latency:
{% include youtubePlayer.html id="kPblRGd8I5Q"%}


**Waypoint acquisition and tracking:** This video illustrates the combination of human input and automatic control; the user selects waypoints on the ellipse, which the device follows using robotic control, faster and more accurately than possible with the human hand:
{% include youtubePlayer.html id="BUr6CHbMZig"%}

The prototype demonstrates the concept well, and the performance was largely as desired. However, further miniaturization would be needed in order to be suitable for minimally invasive surgery, in which smaller diameter is needed (roughly sub centimeter, but smaller depending on the procedure). I also learned a lot about the difficulty of aligning optical components -- seeing the need for modular, repeatable assembly, which would inspire innovation in my [next prototype](mm_laser).
