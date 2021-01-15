---
title: "Piezoelectric flextensional actuators"
#excerpt: "Short description of portfolio item number 1<br/><img src='/images/Laser_scanner.png'>"
permalink: /project/flextensional
collection: projects
header:
  teaser: "Teaser_flextensional_72.png"
---

In this project, I showed how to design and fabricate flextensional piezoelectric actuators on the millimeter scale with similar performance at high transmission ratios as their centimeter-scale counterparts. These actuators convert the large tensile stresses 25 Pa*m/V and small displacements (0.1% strain) generated via the converse piezoelectric effect into larger displacements at the expense of output force. The quality of this conversion, termed "mechanical efficiency", is a key performance metric that I show how to optimize over five generations of actuator development, shown in the figure below. I provide simple guidelines based on lumped parameter modeling and scaling analysis to assist designers in sizing actuators to match specific size and output requirements.

<figure>
    <img src= "{{ "Flextensional_progress.png" | prepend: "/images/" | prepend: base_path }}"
         alt="cm laser scanner"
         style="width:70%">
    <!-- <figcaption>Centimeter laser steering system</figcaption> -->
</figure>

This work enables new millimeter-scale systems and to facilitate the downscaling of existing centimeter-sized devices. These actuators can be used as building blocks in millimeter-sized devices in which precise, linear motion is needed, and the method of analysis employed should be broadly useful to designers of similar devices looking to distill a complex mechanics problem down to a set of simple design guidelines.

The potential applications for these devices on the millimeter scale are numerous, as judged by existing deployments in centimeter-sized systems. Claeyssen, et al. [1], describe a host of device applications: micro-scanning and shutter control for high-speed optical systems, active damping and shape control in aerodynamic systems, and acoustic sourcing for mapping underwater pipe networks and structural health monitoring. Janker, et al. [2] describe a wing morphing mechanism and vibration absorbers for helicopters and automobiles. Liu, et al. [3] and Lee, et al. [4] use flextensional actuators as the basis for in-plane and out-of-plane micropositioning stages, respectively.

**Laser micromachining:** This video shows the use of a galvo-operated UV laser to micromachine the carbon fiber amplification frame. This is the final step of device fabrication, in which the device is released from the multi-material laminate from which it is formed:
{% include youtubePlayer.html id="qqgs0mI19Qw"%}

**Free displacement:** This clip shows the free (unloaded) motion of the actuator. For these type of devices, typical output displacements are ~50-100 um:
{% include youtubePlayer.html id="5S4Af7p4oLY"%}

**Blocked force:** Next, this clip shows the other extreme of actuator performance: fully blocked output, in this case with a force sensor that allows the blocked force to be measured. Any internal motion of the actuator in this configuration represents loss in output work. Typical output force is ~50-100 mN:
{% include youtubePlayer.html id="s_lih4X8WQg"%}

**Spring load:** Lastly, this clip shows an intermediate loading condition: a spring load is attached to the output, and some intermediate force and displacement are achieved in between the extremes of free displacement and blocked force:
{% include youtubePlayer.html id="0hGlI_iiNfk"%}

**Microgripper demonstration:** In this video, pincers are added to the flextensional actuator to enable grasping of small objects. This shows potential usage of this technology in micromanipulation applications:
{% include youtubePlayer.html id="lXAb7RbojAs"%}

<br/><br/>
**References:**
[1] F. Claeyssen, R. L. Letty, F. Barillot, and O. Sosnicki, “Amplified piezoelectric actuators: Static &
dynamic applications,” Ferroelectrics, vol. 351, no. 1, pp. 3–14, 2007.

[2] P. Janker, M. Christmann, F. Hermle, T. Lorkowski, and S. Storm, “Mechatronics using piezoelectric ¨
actuators,” Journal of the European Ceramic Society, vol. 19, no. 6, pp. 1127–1131, 1999.

[3] P. Liu, P. Yan, and Z. Zhang, “Design and analysis of an x–y parallel nanopositioner supporting largestroke servomechanism,” Proceedings of the Institution of Mechanical Engineers, Part C: Journal of
Mechanical Engineering Science, vol. 229, no. 2, pp. 364–376, 2015.

[4] H.-J. Lee, H.-C. Kim, H.-Y. Kim, and D.-G. Gweon, “Optimal design and experiment of a three-axis
out-of-plane nano positioning stage using a new compact bridge-type displacement amplifier,” Review
of Scientific Instruments, vol. 84, no. 11, p. 115103, 2013.
