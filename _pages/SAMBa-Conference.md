---
permalink: /SAMBa-Conference/
title: "SAMBa Conference"
excerpt: "Information for the virtual SAMBa summer conference 2021"
author_profile: false # true #sidebar content
sidebar: 
   title: "Navigation"
   nav: "conf"
redirect_from: 
  - "/sambaconference/"
  - "/sambaconference.html"
  - "/samba-conference.html"

 /* The flip card container - set the width and height to whatever you want. We have added the border property to demonstrate that the flip itself goes out of the box on hover (remove perspective if you don't want the 3D effect */
.flip-card {
  background-color: transparent;
  width: 300px;
  height: 200px;
  border: 1px solid #f1f1f1;
  perspective: 1000px; /* Remove this if you don't want the 3D effect */
}

/* This container is needed to position the front and back side */
.flip-card-inner {
  position: relative;
  width: 100%;
  height: 100%;
  text-align: center;
  transition: transform 0.8s;
  transform-style: preserve-3d;
}

/* Do an horizontal flip when you move the mouse over the flip box container */
.flip-card:hover .flip-card-inner {
  transform: rotateY(180deg);
}

/* Position the front and back side */
.flip-card-front, .flip-card-back {
  position: absolute;
  width: 100%;
  height: 100%;
  -webkit-backface-visibility: hidden; /* Safari */
  backface-visibility: hidden;
}

/* Style the front side (fallback if image is missing) */
.flip-card-front {
  background-color: #bbb;
  color: black;
}

/* Style the back side */
.flip-card-back {
  background-color: dodgerblue;
  color: white;
  transform: rotateY(180deg);
} 


---

# [Welcome and Information](#welcome-and-information) 

![](/kap39.github.io/images/conference20.jpg)

Welcome to the fifth annual SAMBa Summer Conference. This website will be updated with conference details as they are confirmed. 

The SAMBa conference is an opportunity for students to showcase their work to members of the department, outside the department and at other Universities in a supportive environment. The work of SAMBa students covers the entire spectrum of statistical applied mathematics: including projects in statistics, probability, analysis, numerical analysis, mathematical biology, fluid dynamics, machine learning and high-performance computing. The conference is organized by students and contains talks by SAMBa students, external speakers, and students from other departments and institutions. 


## Important Documents
Find important documents here. 

# [Registration](#registration) 
If you would like to attend the conference please complete the registration which can be found [here](https://forms.office.com/Pages/ResponsePage.aspx?id=Ij1-N6FOLUKwrY_MiUBrnrhm9py2vv5OqeESICF49LlUQUQyTVdSODlaVlhORExXQUc4ODQxT05ESyQlQCN0PWcu "Registration Form").

# [Schedule](#schedule)
Coming soon.

# [Speakers](#speakers)
A full list of speakers, and abstracts coming soon.  

# [Coordinators](#coordinators)

The conference is being organised by 4 SAMBa PhD students. If you are interested in attending, giving a talk, or have any questions please feel free to contact any of us 

|Katie Phillips | Shahzeb Raja Noureen | Chris Dean | Yi Sheng Lim | 
|:-------------:|:--------------------:|:----------:|:------------:|
|Fluid dynamics focusing <br> on lubrication layer theory and interfacial waves |Stochastic modelling of melanoblast neural crest cells|Polya urn processes with infinite initial conditions|Spectral theory of random operators|
|kap39 at bath.ac.uk | srn32 at bath.ac.uk | cbcd20 at bath.ac.uk | ysl64 at bath.ac.uk |

{% raw %}
 <div class="flip-card">
  <div class="flip-card-inner">
    <div class="flip-card-front">
      Hello World
    </div>
    <div class="flip-card-back">
      <h1>John Doe</h1>
      <p>Architect & Engineer</p>
      <p>We love that guy</p>
    </div>
  </div>
</div> 
{% endraw %}