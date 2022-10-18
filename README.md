<style>
  :root {
    /* colors */
    --white: #ffffff;
    --red: #e1011c;
    --blue: #0077FF;
    --purple: #da8ee7;
    --accent: rgb(0,0,0);

    /* brandbooks color */
    --vk-bg-color: var(--blue);
    --tg-bg-color: #0088CC;
    --hh-bg-color: var(--red);

    /* any */
    --default-padding: 6px 12px;
    --default-container-bottom-padding: 24px;
    --default-gap: 15px;
  }

  a:hover {
    text-decoration: none;
    color: var(--accent);
  }

  .container {
    width: 100%;
    overflow: hidden;
    padding-top: var(--default-container-bottom-padding);
  }

  .container__social-buttons {
    margin: auto;
    display: grid;
    grid-template-columns: 125px 125px 125px;
    grid-gap: var(--default-gap);
  }

  .button {
    border-radius: 10px; 
    height: 25px;
    outline: none; 
    border: none;
    cursor: pointer;
  }

  .social__button {
    display: flex; 
    justify-content: center; 
    align-items: center;
    padding: var(--default-padding);
    width: auto !important;
    text-decoration: none;
  }

  .social__text-buttons {
    margin-left: 10px;
  }

  .vk__button {
    background: var(--vk-bg-color); 
  }

  .tg__button {
    background: var(--tg-bg-color); 
  }

  .hh__button {
    background: var(--hh-bg-color); 
  }
  
  .vk__button,
  .tg__button,
  .hh__button {
    color: var(--white); 
  }

  .header {
    padding: 0;
  }

  .text__header {
    font-size: 24px;
    margin-bottom: 12px !important;
  }

  .text__title {
    font-size: 18px;
  }

  .text__subtitle {
    font-size: 16.5px;
    padding-bottom: 6px;
  }
  
  .text__paragraph {
    font-size: 15px;
  }

  .text__header, 
  .text__title, 
  .text__subtitle {
    font-weight: bold;
  }
  
  .text__header, 
  .text__title, 
  .text__subtitle, 
  .text__paragraph {
    margin: 0;
  }

  .container__skills {
    display: flex;
    flex-wrap: wrap;
    grid-gap: var(--default-gap);
    margin-bottom: 12px;
  }

  .text__skill {
    padding: var(--default-padding);
    margin: 0;
    background: var(--purple);
    border-radius: 10px;
    color: black;
  }

  @media screen and (max-width: 545px) {
    .container__social-buttons {
      grid-template-columns: 1fr;
    }
  }

</style>

<div class="container header">
  <p class="text__header">Dmitriy Maksimyk</p>
  <p class="text__paragraph">⚒️ Frontend Developer</p>
  <p class="text__paragraph">🎂 23.02.2004</p>
  <p class="text__paragraph">🌐 Perm, Russia</p>
<div>

<div class="container about-me">
  <p class="text__header">👤 About me</p>
  <p class="text__paragraph">
  Hello! My name is Dmitry, I'm a front-end developer. I became interested in front-end development at the age of 15, but I have been interested in IT since I was 11 years old.
  <br/>
  <br/>
  At the moment, I managed to work in the company, participate in competitions and make a couple of my own projects.
  <br/>
  <br/>
  I like to work on interesting problems. In my free time, I study various branches of IT, study English and psychology.
  <br/>
  <br/>
  I dream of working at Yandex and Google as a front-end developer =)</p>
<div>

<div class="container skills">
  <p class="text__header">📊 My Skills</p>

  <p class="text__subtitle">Programming languages</p>
  <div class="container__skills">
    <div class="text__skill">JavaScript ( ES5, ES6, TypeScript )</div>
    <div class="text__skill">Dart</div>
  </div>

  <p class="text__subtitle">Working technologies</p>
  <div class="container__skills">
    <p class="text__skill">HTML</p>
    <p class="text__skill">CSS</p>
    <p class="text__skill">Node JS</p>
    <p class="text__skill">Webpack</p>
    <p class="text__skill">ESBuild</p>
    <p class="text__skill">React JS</p>
    <p class="text__skill">Vue JS</p>
    <p class="text__skill">Next JS</p>
    <p class="text__skill">Express JS</p>
    <p class="text__skill">Fastify JS</p>
    <p class="text__skill">Redux</p>
    <p class="text__skill">Recoil</p>
    <p class="text__skill">PostCSS</p>
    <p class="text__skill">SASS ( SCSS )</p>
    <p class="text__skill">Stylus</p>
    <p class="text__skill">styled-components</p>
    <p class="text__skill">Socket.io</p>
    <p class="text__skill">MongoDB ( Mongoose )</p>
  </div>

  <p class="text__subtitle" style="margin: 0; padding: 0">Other<p>
  <div class="container__skills" style="margin: 0; padding: 0">
    <p class="text__skill">Npm</p>
    <p class="text__skill">Yarn</p>
    <p class="text__skill">Rest</p>
    <p class="text__skill">Git</p>
    <p class="text__skill">CI / CD</p>
    <p class="text__skill">Ubuntu</p>
    <p class="text__skill">Jira</p>
    <p class="text__skill">Flutter</p>
    <p class="text__skill">React Native</p>
    <p class="text__skill">Electron</p>
  </div>
<div>

<div class="container contacts">
  <p class="text__header">📞 Contact me</p>
  <div class="container__social-buttons">
    <a class="button vk__button social__button social__button_margin" href="https://vk.com/id419149056" _target="blank">
      <img src="./assets/vk-logo.png" alt="" width="25px" height="25px">
      <span class="social__text-buttons">VKontakte</span>
    </a>
    <a class="button tg__button social__button social__button_margin" href="https://t.me/d_maksimyk" _target="blank">
      <img src="./assets/tg-logo.png" alt="" width="25px" height="25px">
      <span class="social__text-buttons">Telegram</span>
    </a>
    <a class="button hh__button social__button social__button_margin" href="https://perm.hh.ru/resume/f5f7a20bff0b2688420039ed1f3069454f6135" _target="blank">
      <img src="./assets/hh-logo.png" alt="" width="25px" height="25px">
      <span class="social__text-buttons">HeadHunter</span>
    </a>
  </div>
<div>
