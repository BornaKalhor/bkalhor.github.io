---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  .typewriter {
  font-family: monospace;
  font-weight: bold;
  animation: typing 3s steps(30, end) 1s 1 normal both, blinking-cursor .5s step-end infinite;
}
</style>


<h1 class="typewriter"></h1>


This is Borna, a computer engineering graduate from Ferdowsi University of Mashhad.

My interest areas are in the fields of usable privacy and security, network security, IoT security, and information retrieval. I have taken specialized courses and worked on projects related to these topics during my undergraduate studies.

Through coursework and projects, I have developed proficiency in programming languages like Python, Java, C, and Assembly. I have experience building networking tools, access control systems, search engines, data mining applications, and recommender systems.

Outside of my technical skills, I enjoy staying active by going to the gym and hiking. I find these sports help me relax and recharge after long hours of study. Photography is another hobby of mine, and I like taking landscape photos in particular. I'm also an avid coffee drinker ☕


<script>
  var typewriter = document.querySelector(".typewriter");
  var text = "Hello world.";
  var i = 0;

  function type() {
    if (i < text.length) {
      typewriter.innerHTML += text[i];
      i++;
      setInterval(myFunction, 3000);
    }
  }

  type();
</script>