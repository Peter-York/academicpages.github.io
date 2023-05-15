---
title: "Needlescopic surgical wrists"
#excerpt: "Short description of portfolio item number 1<br/><img src='/images/Laser_scanner.png'>"
permalink: /project/wrists
collection: projects
header:
  teaser: "Teaser_wrist_300.png"
---

This was a project that I worked on as an undergraduate researcher with Prof. Webster at Vanderbilt. His lab had developed an exciting technology called "concentric tube robots", in which nested, pre-curved superelastic nitinol tubes are rotated and translated to access difficult-to-reach parts of the body in minimally invasive surgery, such as the skull base and the lungs. My contribution, conducted under the direction of Phil Swaney, was to develop a simple flexible wrist to enhance the distal dexterity of these devices.

My approach was to use a micro CNC to carefully machine slots in the nitinol tube, which allowed for localized bending using a single pull wire. I also developed a simple statics-based model for predicting the wrist's kinematics.

<figure class="threequarters">
    <img src= "{{ "CNC.jpg" | prepend: "/images/" | prepend: base_path }}">
    <figcaption>Micro CNC with 20 mil titanium carbide end mill and nitinol tube held in aluminum fixture</figcaption>
</figure>

**Teleoperated motion:** This video shows the macroscopic motion of the concentric tube robot combined with the distal bending motion of the wrist:
{% include youtubePlayer.html id="HwKNAwHCBvo"%}

**Skull base access demonstration:** This demonstration shows the value of the wrist in a simulated pituitary resection procedure; the wrist, with a curette attached, gives the user greater dexterity to manipulate the simulated diseased tissue:
{% include youtubePlayer.html id="JfjF_-uRY3w"%}
