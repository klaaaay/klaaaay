<h1 align="left">Hi 👋! My name is Kherroubi Mohamedali , You can call me Klaaay</h1>

###

<h2 align="left">Algerian Full-Stack Web Devloper, since 2019</h2>

###

<h1 align="left">Languages</h1>

###

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="39" alt="javascript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="39" alt="typescript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="39" alt="react logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="39" alt="html5 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="39" alt="css3 logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="39" alt="python logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg" height="39" alt="bootstrap logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/discordjs/discordjs-original.svg" height="39" alt="discordjs logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" height="39" alt="git logo"  />
  <img width="12" />
  <img src="https://cdn.simpleicons.org/webassembly/654FF0" height="39" alt="webassembly logo"  />
  <img width="12" />
  <img src="https://cdn.simpleicons.org/discord/5865F2" height="39" alt="discord logo"  />
</div>

###

<h2 align="left">Social Media</h2>

###

<div align="left">
  <a href="https://www.youtube.com/@KLAAAY_OFF/" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Youtube&logo=youtube&label=&color=FF0000&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="youtube logo"  />
  </a>
  <a href="instagram.com/klaaay_dev" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Instagram&logo=instagram&label=&color=E4405F&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="instagram logo"  />
  </a>
  <a href="https://discord.gg/3vd6qFBucM" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Discord&logo=discord&label=&color=7289DA&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="discord logo"  />
  </a>
  <a href="kherroubimohamedali@gmail.com" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Gmail&logo=gmail&label=&color=D14836&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="gmail logo"  />
  </a>
  <a href="https://www.linkedin.com/in/klaaay-off-4a4875339/" target="_blank">
    <img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&labelColor=&style=for-the-badge" height="35" alt="linkedin logo"  />
  </a>
</div>

###

###
# Visitor Counter

A simple visitor counter built using HTML, CSS, and JavaScript. This counter starts from 2800 and increments by 1 every time the page is loaded. The visitor count is stored locally in the browser using `localStorage`.

## Features
- Starts counting from a specified number (default: 2800).
- Increments the visitor count on each page load.
- Stores the visitor count locally using `localStorage`.

## Code Example


<div style="text-align: center;">
    <h1>عدد الزوار: <span id="visitor-count">2800</span></h1>
</div>

<script>
    // Load the initial number from localStorage or start at 2800
    let visitorCount = localStorage.getItem("visitorCount") 
      ? parseInt(localStorage.getItem("visitorCount")) 
      : 2800;

    // Update the count in the HTML
    document.getElementById("visitor-count").textContent = visitorCount;

    // Increment the count by 1 on each page load
    visitorCount++;
    
    // Store the updated count in localStorage
    localStorage.setItem("visitorCount", visitorCount);
</script>


###
