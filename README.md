## Hi, my name is Samarth 👋

<!--
**sdev138/sdev138** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<style>
.markdown-cube.cube-scene {
  position: relative;
  width: 54px;
  height: 65px;
  margin-bottom: 22px;
  perspective: 240px;
}
.markdown-cube .cube-jump {
  position: absolute;
  left: 13px;
  top: 11px;
  width: 22px;
  height: 22px;
  transform-style: preserve-3d;
}
.markdown-cube .cube {
  width: 100%;
  height: 100%;
  transform-style: preserve-3d;
  transform: rotateX(-24deg) rotateY(35deg);
  animation: markdown-cube-rotate 10s linear infinite;
}
.markdown-cube .cube-face {
  position: absolute;
  inset: 0;
  box-sizing: border-box;
  border: 1px solid var(--body, #565656);
  backface-visibility: hidden;
}
.markdown-cube .cube-face--front {
  background: var(--body, #565656);
  transform: translateZ(11px);
}
.markdown-cube .cube-face--back {
  background: var(--body, #565656);
  transform: rotateY(180deg) translateZ(11px);
}
.markdown-cube .cube-face--right {
  background: var(--ink, #333333);
  transform: rotateY(90deg) translateZ(11px);
}
.markdown-cube .cube-face--left {
  background: var(--ink, #333333);
  transform: rotateY(-90deg) translateZ(11px);
}
.markdown-cube .cube-face--top {
  background: var(--muted, #707070);
  transform: rotateX(90deg) translateZ(11px);
}
.markdown-cube .cube-face--bottom {
  background: var(--ink, #333333);
  transform: rotateX(-90deg) translateZ(11px);
}
.markdown-cube .cube-ground {
  position: absolute;
  left: 11px;
  bottom: 10px;
  width: 26px;
  height: 1px;
  background: var(--line, #d6d6d6);
}

@keyframes markdown-cube-rotate {
  from {
    transform: rotate3d(-1, 1, 0, 0deg) rotateX(-24deg) rotateY(35deg);
  }
  to {
    transform: rotate3d(-1, 1, 0, 360deg) rotateX(-24deg) rotateY(35deg);
  }
}

@media (prefers-reduced-motion: reduce) {
  .markdown-cube .cube {
    animation: none;
  }
}
</style>

<div class="cube-scene markdown-cube" aria-hidden="true">
  <div class="cube-jump">
    <div class="cube">
      <span class="cube-face cube-face--front"></span>
      <span class="cube-face cube-face--back"></span>
      <span class="cube-face cube-face--right"></span>
      <span class="cube-face cube-face--left"></span>
      <span class="cube-face cube-face--top"></span>
      <span class="cube-face cube-face--bottom"></span>
    </div>
  </div>
  <span class="cube-ground"></span>
</div>

#### Currently working as a PM @ Five9 and trying to understand human intelligence 
<!--
Full-Stack Developer at [Medicare](https://medicare.pt?ref=github-caneco);<br>
Host/Organizing [Laracon EU](https://laracon.eu?ref=github-caneco);<br>
--> 
- ⚙️ My daily tools: `.py`, `.cpp`, `.c`, `.html`, `.rs`, `.mojo`, `.vim`, `.go`
- 🌍 I'm always active so contact me whenever
- 💅 Super into design, and love studying the works of Tetsuya Nomura
- 💬 `ping` me about **design**, **DEVim**, or any **Upcoming Features for any and future projects**
- 🌱 Currently learning about Mojo from [Modular](https://www.modular.com/)
- 🔭 Love obsessing over Final Fantasy Versus XIII<br>
[![Gmail Badge](https://img.shields.io/badge/-Email-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:samarthdev138@gmail.com)](samarthdev138@gmail.com)
[![Linkedin Badge](https://img.shields.io/badge/-Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/samarth-dev/)](https://www.linkedin.com/in/samarth-dev/)

[Feel free to check out my website to learn more about me](https://devsamarth.com)

Recently due to massive massive uptime issues on Github, I've been migrating and doing my serious work on [Gitlab](https://gitlab.com/samarthdev). Feel to check those out for my most recent and up to date info.
