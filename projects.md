---
layout: default
title: "Projects"
permalink: /projects/
nav: true
order: 3
---

<div class="home-intro">
  <div class="right-columns">
   <div class="projects-column">
      <h2>Projects</h2>
      <ul>
        <li><strong>Project 1:</strong> Integration of CoppeliaSim for the Da Vinci robot - 2024</li>
      </ul>
      <p>Minimally invasive surgery (MIS), which is more precise and less disruptive than
traditional surgery, has drastically reduced postoperative complications by accelerating
the recovery process. However, this more refined technique is more dependent on
complex instruments and requires more exhaustive planning and training. Therefore,
the creation of simulation environments is of great value. 

This work develops a virtual environment of the Da Vinci surgical
robot modelling the seven degrees of freedom and the working space of the tip of two surgical tools (gripper and scissors). The geometric model implements the direct and inverse kinematics and is validated by testing trajectories with varying degrees of complexity showing the joint range limitation dependencies and collision avoidance. Additionally, a user interface was designed and programmed to allow for external input of a gamepad with several buttons and two joysticks. This enabled real-time manipulation of the surgical tools in the virtual environment on a basic prototype surgical scenario. 

</p>
      <p>The entire project (kinematics, trajectories, external input interface and environment) is programmed in Python.
      <p>- Virtual environment runs on CoppeliaSim interfacing with Python. </p>
      <p>- 3D Model of the DaVinci robot was designed in Fusion 360 following qualitative aspects and relative dimensions of 2009 real model.</p>
      <p>- Temporal resolution of real-time external commands was below perception of user, giving immediate feedback of movement in the simulation (< 150ms).</p>
      <p> ----</p>
      <p></p>
      <p>Precision of the gamepad used was around 1mm. </p>
      <p>- The gripper and the scissors included modelling of applied forces on the tissue mimicking real tissue tolerance to pressure.</p>
      <img src="{{ '/assets/images/davinci.png' | relative_url }}" alt="Your Photo">
      <p> ----</p>
      <p>The project aim was to replicate the behaviour of the Da Vinci robot (2009) in a simulated environment for the purpose of creating a first open source benchmark to develop training environments for surgeons.</p>
      <video width="640" height="360" controls>
        <source src="{{ '/assets/videos/videodavinci.mp4' | relative_url }}" type="video/mp4">
        Tu navegador no soporta la etiqueta de video.
      </video>
    </div>
    <div class="projects-column">
      <ul>
        <li><strong>Project 2:</strong> Image segmentation with a random walker-based algorithm - 2022</li>
      </ul>
      <p>This project will address a problem that is very present in the medical and biomedical sectors. The problem studied in this final degree project (TFG) is how to segment an image into its relevant elements in an automated way to expedite data processing. Medical image segmentation is essential for diagnostic and therapeutic purposes. For diagnostic purposes, examples include the visualization of complex bone fractures, vessel segmentation for 3D visualization, and the diagnosis of vascular malformations. For therapeutic purposes, examples include bone segmentation for the surgical planning of orthopedic procedures and tissue segmentation to distinguish between tumors and adjacent structures for radiotherapy treatment. It can also have educational purposes, such as creating medical atlases. To achieve the segmentation, an algorithm based on the random walker algorithm will be applied.</p>
      <p>Medical image processing has become a fundamental tool for diagnosis and for providing precise image-guided treatments. This work will explore this algorithm to understand its application, limitations, and to optimize its implementation. Additionally, tests will be conducted with this algorithm to evaluate its performance on real medical images.</p>
       <p>Below you can see some examples of the many medical images processed:</p>
    <img src="{{ '/assets/images/segmentacion.png' | relative_url }}" alt="Your Photo">
    <img src="{{ '/assets/images/segmentacion2.png' | relative_url }}" alt="Your Photo">
    </div>
    <div class="projects-column">
      <ul>
        <li><strong>Project 3:</strong> Network clock - 2021</li>
      </ul>
      <p>A tabletop clock will be designed to display hours, minutes, and seconds. It is called a network clock because the time base will be obtained through the frequency available from the 230V AC outlet. The clock will display the time using seven-segment displays that show the data in BCD code. A system will be implemented to set the clock. The clock is implemented in the Proteus simulation program using logic gates and flip-flops. Also dedicated integrated circuits will be used for its implementation. In this case, the dedicated circuits 4510 and 4040 will be used.</object></p>
      <p>The final circuit designed is the one shown below</p>
      <img src="{{ '/assets/images/reloj.png' | relative_url }}" height="540px" alt="Your Photo">
    </div>
    <div class="projects-column">
      <ul>
        <li><strong>Project 4:</strong> Judge - Detective game with Unity3D - 2018</li>
      </ul>
      <p>Judge is a logic, strategy, and puzzle-solving game. In more advanced versions, the educational genre could also be included. Players will control the detective (Henry Bogart). The objective of the game is to find the family in the house. By interacting with objects, players can collect clues (numbers). Each object will have a comment from the detective, which may provide a hint about something the player had not considered. The numbers form a code. This code can be entered into one of the objects in the scene. Entering the code will trigger an animation. The game has a cartoon aesthetic and does not contain any textures except for the paintings. It is planned for release on PC only. The player will control the game using a mouse and keyboard.</p>
      <video width="925" height="500" controls>
        <source src="{{ '/assets/videos/gameunity.mp4' | relative_url }}" type="video/mp4">
        Tu navegador no soporta la etiqueta de video.
      </video>
    </div>
  </div>
</div>
