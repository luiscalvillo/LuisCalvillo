<!--
**luiscalvillo/LuisCalvillo** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:
-->

# Luis Calvillo 

**`iOS Developer `**







<svg fill="none" viewBox="0 0 600 300" width="600" height="300" xmlns="http://www.w3.org/2000/svg">
  <foreignObject width="100%" height="100%">
    <div xmlns="http://www.w3.org/1999/xhtml">
      <style>
        * {
          margin: 0;
          padding: 0;
          color: inherit;
          text-decoration: none;
          list-style: none;
          outline: none;
          box-sizing: border-box;
        }

        .body {
        --color-white: #ffffff;    
          --color-black: #000000;
          --color-main: #46ddc9;
          --color-primary: #468cdd;
          --color-secondary: #c946dd;
          /*--color-background: #333333;*/
          --color-link: #fef29e;
          --color-link-active: #ff4444;

          height: 300px;
          width: 100%;
          text-transform: uppercase;
          display: flex;
          align-items: center;
          justify-content: center;

          background-image: radial-gradient(var(--color-main), var(--color-primary), var(--color-secondary));
          animation: border 10s linear infinite;
          background-size: 200% 200%;
          background-position: 0 0;
          border: 10px solid;
          border-radius: 40px;
          border-color: var(--color-background);
          position: relative;
        }

        .container {
          background: var(--color-background);
          height: calc(100% - 10px);
          width: calc(100% - 10px);
          border-radius: 30px;
          display: flex;
          flex-direction: column;
          justify-content: center;
          align-items: center;
        }

        .notch {
          background: var(--color-black);
          height: 80px;
          width: 20px;
          border-radius: 10px;
          position: absolute;
          top: 100px;
          left: 10px;
        
          animation: intro 1.5s cubic-bezier(0.5, 0, 0.25, 1.3) -1s 1;

        }

        h1 {
          font-size: 3.5rem;
          font-weight: 800;
          font-family: "Open Sans", sans-serif;
          text-align: center;
        }

        h1 a {
          display: block;
        }

        h1 a span {
          overflow: hidden;
          transition: transform 0.25s cubic-bezier(0.5, 0, 0.25, 1.25);
          display: block;
        }

        h1 a span em {
          display: block;
        }

        h1 a span:nth-child(1) {
          color: var(--color-white);
          margin-top: 30px;
          margin-bottom: 6px;
          animation: intro 1.5s cubic-bezier(0.5, 0, 0.25, 1.3) -1s 1;
        }

        h1 a span:nth-child(1) em {
          margin-top: 30px;
          line-height: 0rem;
          margin-bottom: -10px;
        }

        h1 a span:nth-child(2) {
          color: var(--color-black);
          margin-bottom: 6px;
          animation: intro 1.5s cubic-bezier(0.5, 0, 0.25, 1.2) -0.9s 1;
        }

        h1 a span:nth-child(2) em {
          margin-top: -6px;
          line-height: 1rem;
        }

        h1 a span:nth-child(3) {
          color: var(--color-black);
          animation: intro 1.5s cubic-bezier(0.5, 0, 0.25, 1.1) -0.8s 1;
        }

        h1 a span:nth-child(3) em {
          margin-top: -36px;
          line-height: 3rem;
        }

        h1 a:hover span,
        h1 a:focus span {
          transition: transform 0.125s cubic-bezier(0.5, 0, 0.25, 2.5);
        }

        h1 a:hover span:nth-child(1),
        h1 a:focus span:nth-child(1) {
          transform: translateX(1vw);
        }

        h1 a:hover span:nth-child(3),
        h1 a:focus span:nth-child(3) {
          transform: translateX(-1vw);
        }

        .items {
          margin-top: 24px;
          display: flex;
          justify-content: center;
          align-items: center;
          flex-direction: column;
        }

        ul {
          font-size: 32px;
          line-height: 26px;
          color: var(--color-main);
          font-weight: 700;
          font-family: "Open Sans", sans-serif;
        }

        ul li {
          display: flex;
          letter-spacing: 0.125vw;
        }

        ul li a {
          margin-left: 5px;
        }

        ul li a:hover,
        ul li a:focus {
          color: var(--color-link-active);
        }

        ul li a {
          color: var(--color-link);
        }

        .hi {
          display: inline-block;
          transform-origin: 70% 70%;
          animation: hi 3s linear -2s infinite;
        }

        @keyframes border {
          0% {
            background-position: 0 0;
          }

          20% {
            background-position: 100% 0;
          }

          40% {
            background-position: 100% 100%;
          }

          60% {
            background-position: 0 100%;
          }

          100% {
            background-position: 0 0;
          }
        }

        @keyframes hi {
          25% {
            transform: rotate(0deg);
          }

          30% {
            transform: rotate(15deg);
          }

          35% {
            transform: rotate(0deg);
          }

          40% {
            transform: rotate(15deg);
          }

          45% {
            transform: rotate(0deg);
          }

          80% {
            transform: rotate(0deg);
          }

          85% {
            transform: rotate(15deg);
          }

          90% {
            transform: rotate(0deg);
          }

          95% {
            transform: rotate(15deg);
          }

          100% {
            transform: rotate(0deg);
          }
        }

        @keyframes intro {
          0%,
          75% {
            transform: translateX(-100vw);
          }

          100% {
            transform: translateX(0);
          }
        }

        @keyframes fade {
          0%,
          75% {
            opacity: 0;
          }

          100% {
            opacity: 1;
          }
        }

        @media (prefers-color-scheme: light) {
          .body {
            --color-main: #9B5DE5;
            --color-primary: #F15BB5;
            --color-secondary: #00BBF9;
            --color-background: #ffffff;
            --color-link: #00BBF9;
            --color-link-active: #F15BB5;
          }
        }

        @media (prefers-reduced-motion) {
          .body {
            animation: none;
          }

          .hi {
            animation: none;
          }

          ul li {
            opacity: 1;
            animation: none;
          }

          h1 a span:nth-child(1),
          h1 a span:nth-child(2),
          h1 a span:nth-child(3) {
            animation: none;
          }
        }
      </style>
      <div class='body'>
        <div class='notch'></div>
        <div class='container'>
          <h1>
            <a href="https://github.com/luiscalvillo">
              <span>luis calvillo</em></span>
            </a>
          </h1>
          <section class='items'>
            <ul>
              <li>iOS Developer</li>
            </ul>
          </section>
        </div>
      </div>
    </div>
  </foreignObject>
</svg>


I'm a iOS developer with over 8 years of experience. I've published many iOS apps in the App Store and built apps for clients as well.

### Languages and Development Tools

<img align="left" alt="Java" width="50px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/apple/apple-original.svg"/>   
<img align="left" alt="Java" width="50px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/swift/swift-original.svg"/>
<img align="left" alt="Java" width="50px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/xcode/xcode-original.svg"/>
<img align="left" alt="Java" width="50px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/firebase/firebase-plain-wordmark.svg"/>   
<img align="left" alt="Java" width="50px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg"/>   
<img align="left" alt="Java" width="50px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/figma/figma-original.svg"/>
<img align="left" alt="Java" width="50px" style="padding-right:10px;" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/illustrator/illustrator-plain.svg"/>   


### My Lastest Development Articles

<p align="left">

  <a href="https://luiscalvillo.medium.com/bringing-your-app-to-life-a-starter-guide-to-animations-with-swiftui-9876ffa9f071">
    <h3>Bringing Your App to Life: A Starter Guide to Animations with SwiftUI</h3>
  </a>In the world of mobile apps, animations are not just about aesthetics — they play a crucial role in user experience. They can...
</p>
  <a href="https://luiscalvillo.medium.com/bringing-your-app-to-life-a-starter-guide-to-animations-with-swiftui-9876ffa9f071">
    <img src="https://miro.medium.com/v2/resize:fill:160:107/1*sYuTRtafYlt8LAwP-uH5_A.jpeg" alt="Blog Post Image" style="float: right; margin-left: 20px; max-width: 150px; max-height: 150px; object-fit: cover;">
  </a>
