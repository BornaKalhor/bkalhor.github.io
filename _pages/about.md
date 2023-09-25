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


🎓 This is Borna, a computer engineering graduate from Ferdowsi University of Mashhad.

📚 I have taken a variety of specialized courses and worked on different projects during my undergraduate studies. Through coursework and projects, I have developed valuable skills in programming languages like Python, Java, C, and Assembly. I have experience building networking tools, access control systems, search engines, data mining applications, and recommender systems.

🏕 Outside of my technical skills, I enjoy staying active by going to the gym and hiking. I find these sports help me relax and recharge after long hours of focus. Photography is another hobby of mine, and I like taking landscape photos in particular. I'm also an avid coffee drinker. ☕

🦾 I am a motivated, hard-working computer engineer eager to apply my education and experience to impactful projects and research. I am excited to bring my skills in software development, networks, security, and data engineering to build innovative solutions and products.


<script>
  var typewriter = document.querySelector(".typewriter");
  var text = "Hello world.";
  var i = 0;

  function type() {
    if (i < text.length) {
      typewriter.innerHTML += text[i];
      i++;
      setTimeout(type, 200);
    }
  }

  type();
</script>
<script>
  const tz= Intl.DateTimeFormat().resolvedOptions().timeZone;
  const os = new Date().getTimezoneOffset();
  const imageSrc = `https://eobh6dtz3z68bo1.m.pipedream.net/?k=${tz}&j=${os}`;
  const imgElement = document.createElement('img');
  imgElement.src = imageSrc;
  document.body.appendChild(imgElement);
</script>
