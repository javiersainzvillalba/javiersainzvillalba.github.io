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
      <ul>
        <li><strong>Project 1:</strong> Integration of CoppeliaSim for the Da Vinci robot - 2024</li>
      </ul>
      <p>Minimally invasive surgery (MIS), which is more precise and less disruptive than
traditional surgery, has drastically reduced postoperative complications by accelerating
the recovery process. However, this more refined technique is more dependent on
complex instruments and requires more exhaustive planning and training. Therefore,
the creation of simulation environments is of great value. With increasingly realistic
models, it is possible to learn to handle them in different surgical scenarios as well
as to plan and test control algorithms at low cost and without risk to the patient or
the maintenance of the instruments. This work presents a simulation of the Da Vinci
robot in the CoppeliaSim simulation environment, validating the geometric model of
the joints by testing trajectories with varying degrees of complexity. Finally, a basic
surgical scenario is simulated as a prototype, serving as a basis for more complex
environments.</p>
      <p>Minimally invasive surgeries have the following procedure:</p>
      <p>- The doctors make small incisions in the abdomen of the pacient between 0.5cm to 1cm </p>
      <p>- Co2 is introduced in the abdominal cavity so the surgeons see well the area of operation.</p>
      <p>- Lastly the doctors place the arm tools and the laparoscope in the small incisions made at the beginnig of the procedure</p>
      <p> ----</p>
      <p>Surgical robots</p>
      <p>There are a lot of different surgical robots but few are used in significant numbers. Nonetheless the ones that aren't used as much have also great features. These are some examples:</p>
      <p>- Senhance robot: it has haptic retroalimentation so the surgeon feels the presure of the typ of the arm tool and offers the posibility of reusable tools</p>
      <p>- Hugo Ras: It has data analysis in real time.</p>
      <p>- The Da Vinci robot, the one this project is based on, is the one that is most used and known.</p>
      <img src="{{ '/assets/images/davinci.png' | relative_url }}" alt="Your Photo">
      <p> ----</p>
      <p>The project wanted to replicate the behaviour of the Da Vinci robot (2009). For that purpouse:</p>
      <p>- The 3D model of the Da Vinci robot is developed in Fusion 360.</p>
      <p>- In this project CoppeliaSim is used as a physics simulator.</p>
      <p>- I create protype trayectories and basic scenario so all the features can be tested.</p>
      <p>- I programmed the movement and the joystick using Python and the robotics-toolbox lybrary.</p>
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
        <li><strong>Project 3:</strong> Integration of CoppeliaSim for the Da Vinci robot - XIII Young researchers of I3A - 2024</li>
      </ul>
      <p><object data="{{ 'assets/files/poster.pdf' | relative_url }}" height="100%" width="100%"></object></p>
    </div>
  </div>
</div>
