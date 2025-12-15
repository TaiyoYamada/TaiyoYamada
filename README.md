<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:220044,100:6600AA&text=Taiyo%20Yamada&fontSize=60&fontAlign=50&fontAlignY=40&animation=twinkling&desc=Developer&descAlignY=60&descColor=A9A4FE" />
</p>

<svg viewBox="0 0 1200 300" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="grad1" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#220044"/>
      <stop offset="100%" stop-color="#6600AA"/>
    </linearGradient>

    <linearGradient id="grad2" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#3A0077" stop-opacity="0.8"/>
      <stop offset="100%" stop-color="#9B5CFF" stop-opacity="0.8"/>
    </linearGradient>

    <!-- 波パス -->
    <path id="wave"
      d="M0,170 C150,120 300,220 450,170
         C600,120 750,220 900,170
         C1050,120 1200,220 1350,170
         L1350,0 L0,0 Z"/>
  </defs>

  <!-- 背景波（速い） -->
  <g fill="url(#grad1)">
    <use href="#wave" x="0">
      <animateTransform
        attributeName="transform"
        type="translate"
        from="0 0"
        to="-450 0"
        dur="3s"
        repeatCount="indefinite"/>
    </use>

    <use href="#wave" x="450">
      <animateTransform
        attributeName="transform"
        type="translate"
        from="0 0"
        to="-450 0"
        dur="3s"
        repeatCount="indefinite"/>
    </use>
  </g>

  <!-- 前景波（さらに速い・薄め） -->
  <g fill="url(#grad2)">
    <use href="#wave" x="0" y="10">
      <animateTransform
        attributeName="transform"
        type="translate"
        from="0 0"
        to="-300 0"
        dur="2s"
        repeatCount="indefinite"/>
    </use>

    <use href="#wave" x="300" y="10">
      <animateTransform
        attributeName="transform"
        type="translate"
        from="0 0"
        to="-300 0"
        dur="2s"
        repeatCount="indefinite"/>
    </use>
  </g>
</svg>


<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=900&color=C780FF&center=true&vCenter=true&width=750&height=50&size=25&lines=I+am+passionate+about+Swift.;My+research+theme+is+Quantum+Algorithms." />
</p>

<br>
<br>


<p align="center">
  <img src="https://img.shields.io/badge/Age-20-A9A4FE?style=for-the-badge&logoColor=black" />
  <a href="https://qiita.com/TaiyoYamada" target="_blank">
    <img src="https://img.shields.io/badge/Qiita-Link-55C500?style=for-the-badge&logo=qiita&logoColor=white" />
  </a>
</p>


<br>
<br>


<div align="center">
  <a href="https://github.com/TaiyoYamada">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=TaiyoYamada&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&card_height=220" alt="Top Languages" />
  </a>
</div>


<br>
<br>


<p align="center">
  <img height="40" src="https://skillicons.dev/icons?i=swift,flutter,python,html,css,ts,vue,laravel,mysql,aws,docker,cloudflare" />
</p>
