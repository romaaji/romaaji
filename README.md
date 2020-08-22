<html lang="en"><head>
<meta charset="UTF-8">
<link rel="apple-touch-icon" type="image/png" href="https://static.codepen.io/assets/favicon/apple-touch-icon-5ae1a0698dcc2402e9712f7d01ed509a57814f994c660df9f7a952f3060705ee.png">
<meta name="apple-mobile-web-app-title" content="CodePen">
<link rel="shortcut icon" type="image/x-icon" href="https://static.codepen.io/assets/favicon/favicon-aec34940fbc1a6e787974dcd360f2c6b63348d4b1f4e06c77743096d55480f33.ico">
<link rel="mask-icon" type="" href="https://static.codepen.io/assets/favicon/logo-pin-8f3771b1072e3c38bd662872f6b673a722f4b3ca2421637d5596661b4e2132cc.svg" color="#111">
<title>CodePen - Bongo Cat Codes #2 - Jamming</title>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/normalize/5.0.0/normalize.min.css">
<style>
:root {
  --bg: #1a1e2d;
  --green: #a5ea9b;
  --pink: #ff61d8;
  --blue: #569cfa;
  --orange: #ffcc81;
  --cyan: #7ed1e2;
}

body {
  height: 100vh;
  width: 100vw;
  background: var(--bg);
  display: -webkit-box;
  display: flex;
  place-content: center;
  -webkit-box-align: end;
          align-items: flex-end;
}

.container {
  width: 80vw;
  height: 80vh;
}
.container svg {
  height: 100%;
  width: 100%;
  overflow: visible;
}

#bongo-cat {
  fill: var(--bg);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: 4;
}
#bongo-cat .laptop-cover,
#bongo-cat .headphone .band {
  fill: none;
}
#bongo-cat .paw, #bongo-cat .head {
  stroke: var(--orange);
}
#bongo-cat .laptop-keyboard {
  stroke-width: 2;
}
#bongo-cat .terminal-code {
  stroke-width: 5;
}
#bongo-cat .music .note,
#bongo-cat .laptop-base,
#bongo-cat .laptop-cover,
#bongo-cat .paw .pads {
  stroke: var(--pink);
}
#bongo-cat .table line,
#bongo-cat .headphone .band,
#bongo-cat .headphone .speaker path:nth-child(3) {
  stroke: var(--green);
}
#bongo-cat .terminal-frame,
#bongo-cat .laptop-keyboard,
#bongo-cat .headphone .speaker path:nth-child(2) {
  stroke: var(--blue);
}
#bongo-cat .terminal-code,
#bongo-cat .headphone .speaker path:first-child {
  stroke: var(--cyan);
}
</style>
<script>
  window.console = window.console || function(t) {};
</script>
<script>
  if (document.location.search.match(/type=embed/gi)) {
    window.parent.postMessage("resize", "*");
  }
</script>
</head>
<body translate="no">
<div class="container">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 785.5 465.8">
<g id="bongo-cat">
<g class="head">
<path d="M280.4,221l383.8,62.6a171.4,171.4,0,0,0-9.2-40.5,174,174,0,0,0-28.7-50.5,163.3,163.3,0,0,0,3.2-73.8c-11.6-1.9-42,14.2-44.5,17.5-19.6-24-88.5-52.7-153.7-48.1A78.8,78.8,0,0,0,398,67.1c-9.8,2.9-19,29.7-19.4,33.7a320,320,0,0,0-31.7,23.6c-14,11.8-28.9,24.4-42.5,44.3A173,173,0,0,0,280.4,221Z"></path>
<path d="M396.6,178.6c.4.9,2.7,6.5,8.5,8.4s13.4-1.2,17.2-7.9c-.9,7.5,3.8,14.3,10.4,16a14.4,14.4,0,0,0,15-5.7"></path>
<path d="M474,179.2a6.6,6.6,0,0,0-4.9,3.6,6,6,0,0,0,1.5,7.3,6,6,0,0,0,7.9-1c2.3-2.6,2-7,.2-8s-5.9,1.6-5.7,3.5,1.9,2.8,3.2,2.3,1.1-2.2,1.1-2.3"></path>
<path d="M365.4,168.9c0,.3-.8,3.6,1.5,6a5.9,5.9,0,0,0,7.2,1.4,6.1,6.1,0,0,0,2.2-7.7c-1.5-3.1-5.7-4.5-7.3-3.2s-.8,6,1,6.6,3.3-.7,3.3-2.1-1.5-1.8-1.6-1.9"></path>
<g class="headphone headphone-right">
<g class="speaker">
<path d="M400.7,80.2c-14.1-20.8-40.2.3-50.7,15-8.7,12.2-9.7,30.3,2.8,37.3,5.4-9,11.8-15.6,21-26.2A214.1,214.1,0,0,1,400.7,80.2Z"></path>
<path d="M381.5,79.4c-6.6-7.5-9.6-5.8-12.3-5.5-16.3,1.3-32,20.3-27.8,33.9a21.8,21.8,0,0,0,5.9,8.5c1.7-2.6,3.5-5.1,5.4-7.7A150.7,150.7,0,0,1,381.5,79.4Z"></path>
<path d="M367.3,77.8a13.1,13.1,0,0,0-5.1-1.8c-8.5-.9-18.7,7.5-18.4,16.1a12.8,12.8,0,0,0,2.6,7c3.1-3.3,6.3-6.8,9.6-10.2S363.6,81.3,367.3,77.8Z"></path>
</g>
<path class="band" d="M515,40.6c-15.9-4.6-57-14.1-104,2.3a166.9,166.9,0,0,0-60.9,37.3"></path>
</g>
</g>
<g class="music music-right">
<g class="note" style="transform-origin: 0px 0px 0px; opacity: 0.1386; visibility: inherit; stroke: rgb(86, 156, 250);" data-svg-origin="350.79998779296875 46.5" transform="matrix(0.63925,-0.57738,0.57738,0.63925,145.49473,42.73687)">
<g>
<path d="M368.5,46.5c.5,2.1,1.2,3.5,3.8,6.3s5.1,4.3,6.5,7.2a11.1,11.1,0,0,1,.7,2,10.5,10.5,0,0,1-.7,6.5"></path>
<path d="M368.5,46.5a20.8,20.8,0,0,0,2.4,11.7c2.3,4.4,5,5.4,6.8,9.5a17.5,17.5,0,0,1,.4,11"></path>
<line x1="368.5" y1="47.7" x2="368.5" y2="92.8"></line>
<path d="M368.5,92.8c.1-3.1-4.7-6.3-9-6.3s-8.7,2.7-8.7,5.8,4.8,5.7,8.7,5.8S368.3,95.8,368.5,92.8Z"></path>
</g>
<g>
<path d="M368.5,46.5c.5,2.1,1.2,3.5,3.8,6.3s5.1,4.3,6.5,7.2a11.1,11.1,0,0,1,.7,2,10.5,10.5,0,0,1-.7,6.5"></path>
<path d="M368.5,46.5a20.8,20.8,0,0,0,2.4,11.7c2.3,4.4,5,5.4,6.8,9.5a17.5,17.5,0,0,1,.4,11"></path>
<line x1="368.5" y1="47.7" x2="368.5" y2="92.8"></line>
<path d="M368.5,92.8c.1-3.1-4.7-6.3-9-6.3s-8.7,2.7-8.7,5.8,4.8,5.7,8.7,5.8S368.3,95.8,368.5,92.8Z"></path>
</g>
</g>
<g class="note" style="transform-origin: 0px 0px 0px; opacity: 0.935; visibility: inherit; stroke: rgb(86, 156, 250);" data-svg-origin="332.5986633300781 43.5" transform="matrix(0.0472,0.04469,-0.04469,0.0472,296.20402,13.06297)">
<g>
<polyline points="350 81.7 350 43.5 382.7 50.7 382.7 89.5"></polyline>
<path d="M350,82.3c0-3.1-4.5-5.7-8.2-5.9s-9.3,2.8-9.2,6,4.7,5.7,8.6,5.7S349.9,85.5,350,82.3Z"></path>
<path d="M382.7,89.9c0-3.1-4.4-5.7-8.2-5.8s-9.3,2.7-9.2,5.9,4.7,5.7,8.7,5.7S382.7,93.1,382.7,89.9Z"></path>
</g>
<g>
<polyline points="350 81.7 350 43.5 382.7 50.7 382.7 89.5"></polyline>
<path d="M350,82.3c0-3.1-4.5-5.7-8.2-5.9s-9.3,2.8-9.2,6,4.7,5.7,8.6,5.7S349.9,85.5,350,82.3Z"></path>
<path d="M382.7,89.9c0-3.1-4.4-5.7-8.2-5.8s-9.3,2.7-9.2,5.9,4.7,5.7,8.7,5.7S382.7,93.1,382.7,89.9Z"></path>
</g>
</g>
<g class="note" style="transform-origin: 0px 0px 0px; opacity: 1; visibility: inherit; stroke: rgb(253, 124, 110);" data-svg-origin="337.4986267089844 34.599998474121094" transform="matrix(0,0,0,0,315.49863,34.6)">
<polyline points="388.2 73.6 388.2 34.6 354.9 42.6 354.9 82.4"></polyline>
<path d="M388.2,74.1c0-3-4.4-5.6-8.1-5.8s-9.2,2.8-9.1,6,4.6,5.6,8.6,5.6S388.2,77.3,388.2,74.1Z"></path>
<path d="M354.9,81.9c0-3.1-4.4-5.7-8.2-5.9s-9.3,2.8-9.2,6,4.7,5.7,8.7,5.7S354.9,85.1,354.9,81.9Z"></path>
<line x1="354.9" y1="48.4" x2="388.2" y2="40.3"></line>
<line x1="354.9" y1="54.6" x2="388.2" y2="47"></line>
</g>
<g class="note" style="transform-origin: 0px 0px 0px; opacity: 1; visibility: inherit; stroke: rgb(163, 164, 236);" data-svg-origin="354.29864501953125 33.29999923706055" transform="matrix(0,0,0,0,343.29865,33.3)">
<g>
<path d="M371.8,79.5c0-3.1-4.5-5.8-8.3-5.9s-9.3,2.8-9.2,6,4.7,5.7,8.7,5.7S371.8,82.7,371.8,79.5Z"></path>
<line x1="371.8" y1="79.5" x2="371.8" y2="33.3"></line>
<path d="M371.8,33.4a26.6,26.6,0,0,0,3.6,7.8c3.7,5.7,7.6,7,8.8,11.6.5,1.7.7,4.4-.9,8.3"></path>
</g>
<g>
<path d="M371.8,79.5c0-3.1-4.5-5.8-8.3-5.9s-9.3,2.8-9.2,6,4.7,5.7,8.7,5.7S371.8,82.7,371.8,79.5Z"></path>
<line x1="371.8" y1="79.5" x2="371.8" y2="33.3"></line>
<path d="M371.8,33.4a26.6,26.6,0,0,0,3.6,7.8c3.7,5.7,7.6,7,8.8,11.6.5,1.7.7,4.4-.9,8.3"></path>
</g>
</g>
<g class="note" style="transform-origin: 0px 0px 0px; opacity: 0.1916; visibility: inherit; stroke: rgb(255, 204, 129);" data-svg-origin="350.79998779296875 46.5" transform="matrix(0.71237,0.38215,-0.38215,0.71237,164.05018,-298.53912)">
<g>
<path d="M368.5,46.5c.5,2.1,1.2,3.5,3.8,6.3s5.1,4.3,6.5,7.2a11.1,11.1,0,0,1,.7,2,10.5,10.5,0,0,1-.7,6.5"></path>
<path d="M368.5,46.5a20.8,20.8,0,0,0,2.4,11.7c2.3,4.4,5,5.4,6.8,9.5a17.5,17.5,0,0,1,.4,11"></path>
<line x1="368.5" y1="47.7" x2="368.5" y2="92.8"></line>
<path d="M368.5,92.8c.1-3.1-4.7-6.3-9-6.3s-8.7,2.7-8.7,5.8,4.8,5.7,8.7,5.8S368.3,95.8,368.5,92.8Z"></path>
</g>
<g>
<path d="M368.5,46.5c.5,2.1,1.2,3.5,3.8,6.3s5.1,4.3,6.5,7.2a11.1,11.1,0,0,1,.7,2,10.5,10.5,0,0,1-.7,6.5"></path>
<path d="M368.5,46.5a20.8,20.8,0,0,0,2.4,11.7c2.3,4.4,5,5.4,6.8,9.5a17.5,17.5,0,0,1,.4,11"></path>
<line x1="368.5" y1="47.7" x2="368.5" y2="92.8"></line>
<path d="M368.5,92.8c.1-3.1-4.7-6.3-9-6.3s-8.7,2.7-8.7,5.8,4.8,5.7,8.7,5.8S368.3,95.8,368.5,92.8Z"></path>
</g>
</g><g class="note" style="transform-origin: 0px 0px 0px; opacity: 0; visibility: hidden; stroke: rgb(103, 181, 192);" data-svg-origin="350.79998779296875 46.5" transform="matrix(0.66913,0.74314,-0.74314,0.66913,181.6252,-465.30805)">
<g>
<path d="M368.5,46.5c.5,2.1,1.2,3.5,3.8,6.3s5.1,4.3,6.5,7.2a11.1,11.1,0,0,1,.7,2,10.5,10.5,0,0,1-.7,6.5"></path>
<path d="M368.5,46.5a20.8,20.8,0,0,0,2.4,11.7c2.3,4.4,5,5.4,6.8,9.5a17.5,17.5,0,0,1,.4,11"></path>
<line x1="368.5" y1="47.7" x2="368.5" y2="92.8"></line>
<path d="M368.5,92.8c.1-3.1-4.7-6.3-9-6.3s-8.7,2.7-8.7,5.8,4.8,5.7,8.7,5.8S368.3,95.8,368.5,92.8Z"></path>
</g>
<g>
<path d="M368.5,46.5c.5,2.1,1.2,3.5,3.8,6.3s5.1,4.3,6.5,7.2a11.1,11.1,0,0,1,.7,2,10.5,10.5,0,0,1-.7,6.5"></path>
<path d="M368.5,46.5a20.8,20.8,0,0,0,2.4,11.7c2.3,4.4,5,5.4,6.8,9.5a17.5,17.5,0,0,1,.4,11"></path>
<line x1="368.5" y1="47.7" x2="368.5" y2="92.8"></line>
<path d="M368.5,92.8c.1-3.1-4.7-6.3-9-6.3s-8.7,2.7-8.7,5.8,4.8,5.7,8.7,5.8S368.3,95.8,368.5,92.8Z"></path>
</g>
</g><g class="note" style="transform-origin: 0px 0px 0px; opacity: 1; visibility: inherit; stroke: rgb(126, 209, 226);" data-svg-origin="332.5986633300781 43.5" transform="matrix(0,0,0,0,342.59866,43.5)">
<g>
<polyline points="350 81.7 350 43.5 382.7 50.7 382.7 89.5"></polyline>
<path d="M350,82.3c0-3.1-4.5-5.7-8.2-5.9s-9.3,2.8-9.2,6,4.7,5.7,8.6,5.7S349.9,85.5,350,82.3Z"></path>
<path d="M382.7,89.9c0-3.1-4.4-5.7-8.2-5.8s-9.3,2.7-9.2,5.9,4.7,5.7,8.7,5.7S382.7,93.1,382.7,89.9Z"></path>
</g>
<g>
<polyline points="350 81.7 350 43.5 382.7 50.7 382.7 89.5"></polyline>
<path d="M350,82.3c0-3.1-4.5-5.7-8.2-5.9s-9.3,2.8-9.2,6,4.7,5.7,8.6,5.7S349.9,85.5,350,82.3Z"></path>
<path d="M382.7,89.9c0-3.1-4.4-5.7-8.2-5.8s-9.3,2.7-9.2,5.9,4.7,5.7,8.7,5.7S382.7,93.1,382.7,89.9Z"></path>
</g>
</g><g class="note" style="transform-origin: 0px 0px 0px; opacity: 0; visibility: hidden; stroke: rgb(86, 156, 250);" data-svg-origin="332.5986633300781 43.5" transform="matrix(0.40674,0.91355,-0.91355,0.40674,303.05691,-498.0387)">
<g>
<polyline points="350 81.7 350 43.5 382.7 50.7 382.7 89.5"></polyline>
<path d="M350,82.3c0-3.1-4.5-5.7-8.2-5.9s-9.3,2.8-9.2,6,4.7,5.7,8.6,5.7S349.9,85.5,350,82.3Z"></path>
<path d="M382.7,89.9c0-3.1-4.4-5.7-8.2-5.8s-9.3,2.7-9.2,5.9,4.7,5.7,8.7,5.7S382.7,93.1,382.7,89.9Z"></path>
</g>
<g>
<polyline points="350 81.7 350 43.5 382.7 50.7 382.7 89.5"></polyline>
<path d="M350,82.3c0-3.1-4.5-5.7-8.2-5.9s-9.3,2.8-9.2,6,4.7,5.7,8.6,5.7S349.9,85.5,350,82.3Z"></path>
<path d="M382.7,89.9c0-3.1-4.4-5.7-8.2-5.8s-9.3,2.7-9.2,5.9,4.7,5.7,8.7,5.7S382.7,93.1,382.7,89.9Z"></path>
</g>
</g><g class="note" style="transform-origin: 0px 0px 0px; opacity: 1; visibility: inherit; stroke: rgb(255, 204, 129);" data-svg-origin="337.4986267089844 34.599998474121094" transform="matrix(0,0,0,0,323.49863,34.6)">
<polyline points="388.2 73.6 388.2 34.6 354.9 42.6 354.9 82.4"></polyline>
<path d="M388.2,74.1c0-3-4.4-5.6-8.1-5.8s-9.2,2.8-9.1,6,4.6,5.6,8.6,5.6S388.2,77.3,388.2,74.1Z"></path>
<path d="M354.9,81.9c0-3.1-4.4-5.7-8.2-5.9s-9.3,2.8-9.2,6,4.7,5.7,8.7,5.7S354.9,85.1,354.9,81.9Z"></path>
<line x1="354.9" y1="48.4" x2="388.2" y2="40.3"></line>
<line x1="354.9" y1="54.6" x2="388.2" y2="47"></line>
</g><g class="note" style="transform-origin: 0px 0px 0px; opacity: 1; visibility: inherit; stroke: rgb(126, 209, 226);" data-svg-origin="337.4986267089844 34.599998474121094" transform="matrix(0,0,0,0,342.49863,34.6)">
<polyline points="388.2 73.6 388.2 34.6 354.9 42.6 354.9 82.4"></polyline>
<path d="M388.2,74.1c0-3-4.4-5.6-8.1-5.8s-9.2,2.8-9.1,6,4.6,5.6,8.6,5.6S388.2,77.3,388.2,74.1Z"></path>
<path d="M354.9,81.9c0-3.1-4.4-5.7-8.2-5.9s-9.3,2.8-9.2,6,4.7,5.7,8.7,5.7S354.9,85.1,354.9,81.9Z"></path>
<line x1="354.9" y1="48.4" x2="388.2" y2="40.3"></line>
<line x1="354.9" y1="54.6" x2="388.2" y2="47"></line>
</g><g class="note" style="transform-origin: 0px 0px 0px; opacity: 0.3875; visibility: inherit; stroke: rgb(255, 204, 129);" data-svg-origin="354.29864501953125 33.29999923706055" transform="matrix(0.6103,-0.05192,0.05192,0.6103,182.19205,-94.1934)">
<g>
<path d="M371.8,79.5c0-3.1-4.5-5.8-8.3-5.9s-9.3,2.8-9.2,6,4.7,5.7,8.7,5.7S371.8,82.7,371.8,79.5Z"></path>
<line x1="371.8" y1="79.5" x2="371.8" y2="33.3"></line>
<path d="M371.8,33.4a26.6,26.6,0,0,0,3.6,7.8c3.7,5.7,7.6,7,8.8,11.6.5,1.7.7,4.4-.9,8.3"></path>
</g>
<g>
<path d="M371.8,79.5c0-3.1-4.5-5.8-8.3-5.9s-9.3,2.8-9.2,6,4.7,5.7,8.7,5.7S371.8,82.7,371.8,79.5Z"></path>
<line x1="371.8" y1="79.5" x2="371.8" y2="33.3"></line>
<path d="M371.8,33.4a26.6,26.6,0,0,0,3.6,7.8c3.7,5.7,7.6,7,8.8,11.6.5,1.7.7,4.4-.9,8.3"></path>
</g>
</g><g class="note" style="transform-origin: 0px 0px 0px; opacity: 1; visibility: inherit; stroke: rgb(165, 234, 155);" data-svg-origin="354.29864501953125 33.29999923706055" transform="matrix(0,0,0,0,343.29865,33.3)">
<g>
<path d="M371.8,79.5c0-3.1-4.5-5.8-8.3-5.9s-9.3,2.8-9.2,6,4.7,5.7,8.7,5.7S371.8,82.7,371.8,79.5Z"></path>
<line x1="371.8" y1="79.5" x2="371.8" y2="33.3"></line>
<path d="M371.8,33.4a26.6,26.6,0,0,0,3.6,7.8c3.7,5.7,7.6,7,8.8,11.6.5,1.7.7,4.4-.9,8.3"></path>
</g>
<g>
<path d="M371.8,79.5c0-3.1-4.5-5.8-8.3-5.9s-9.3,2.8-9.2,6,4.7,5.7,8.7,5.7S371.8,82.7,371.8,79.5Z"></path>
<line x1="371.8" y1="79.5" x2="371.8" y2="33.3"></line>
<path d="M371.8,33.4a26.6,26.6,0,0,0,3.6,7.8c3.7,5.7,7.6,7,8.8,11.6.5,1.7.7,4.4-.9,8.3"></path>
</g>
</g></g>
<g class="table">
<polyline points="27.3 160.5 785.2 295 785.4 465.8"></polyline>
<line x1="785.2" y1="295" x2="27.3" y2="160.5"></line>
</g>
<polygon class="laptop-base" points="103.2 263.6 258.9 219.3 636.5 294.4 452.1 339 103.2 263.6"></polygon>
<g class="laptop-keyboard">
<polygon points="369.6 265.6 255.3 244.3 255.5 243.5 264.7 241.9 380.9 262.3 380.8 263.1 369.6 265.6"></polygon>
<polygon points="235.9 256.4 219.8 253.2 219.9 252.5 228.7 251 245.3 253.4 245.1 254.2 235.9 256.4"></polygon>
<polygon points="473.1 303.7 248.4 258.9 248.6 258.1 257.7 256.6 486.2 300.4 486 301.3 473.1 303.7"></polygon>
<polygon points="410.3 300.2 202.7 257.5 202.9 256.8 211.4 255.3 422.4 297.1 422.2 298 410.3 300.2"></polygon>
<polygon points="448.5 308.1 427 303.7 427.3 302.8 439.2 301.4 461.2 304.9 461 305.8 448.5 308.1"></polygon>
<polygon points="200.1 264.7 186 261.7 186.2 261 194.5 259.5 208.9 261.8 208.8 262.5 200.1 264.7"></polygon>
<polygon points="221.1 269.1 206.6 266.1 206.8 265.3 215.4 263.9 230.3 266.2 230.1 267 221.1 269.1"></polygon>
<polygon points="361.4 298.9 230 271 230.2 270.3 239.2 268.9 372.7 295.9 372.5 296.7 361.4 298.9"></polygon>
<polygon points="442.8 279.2 383.7 268.2 383.9 267.3 395.1 265.7 455.4 275.9 455.2 276.7 442.8 279.2"></polygon>
<polygon points="524.6 294.4 458.6 282.1 458.8 281.2 471.3 279.7 538.6 291 538.4 291.9 524.6 294.4"></polygon>
<polygon points="424.7 312.4 374.6 301.7 374.8 300.9 385.9 299.5 437 309.3 436.8 310.2 424.7 312.4"></polygon>
<polygon points="409.1 277.3 397.6 278.8 397.4 279.6 498.4 299.1 511.8 296.7 512 295.8 409.1 277.3"></polygon>
<polygon points="394.2 274.5 394.4 273.6 246.7 246.5 237.7 248.1 237.5 248.8 382.8 276.8 394.2 274.5"></polygon>
</g>
<g class="paw paw-right">
<path class="down" d="M289.1,181.7c-12.1,9.8-20.6,20.7-20.7,32.1-.2,9,3.8,20.4,13.3,25.2s20.1.6,29.6-3.4c13.4-5.7,23.9-14.6,29.4-21.5" style="opacity: 0; visibility: hidden;"></path>
<g class="up" style="opacity: 1; visibility: inherit;">
<path d="M327.3,170c-.4-1.4-6.3-18.8-23.5-23.5-.8-.2-18.6-4.7-28.9,6.3-8.4,9.1-6,22.5-4.6,30.2a54.3,54.3,0,0,0,8.1,19.9"></path>
<g class="pads">
<path d="M297.2,154.8c1-.5,2.7-.1,3,.6s-1.4,2.4-2.6,2.1a1.6,1.6,0,0,1-1.1-1.2A1.6,1.6,0,0,1,297.2,154.8Z"></path>
<path d="M285.8,159.4c.3-.4,1-1.1,1.7-.8s.9,1.4.8,2.2-1.8,2.1-2.5,1.5S285.2,160.4,285.8,159.4Z"></path>
<path d="M276.9,171c.5-.4,2.7-.3,3.2.6s-.6,1.8-1.4,1.8S276.2,171.6,276.9,171Z"></path>
<path d="M296.4,168.6c2.3-.9,6.4,6.3,7.6,9s-5.2,4.5-7.4,6-5.1-6.1-5.9-8.3S293.7,169.8,296.4,168.6Z"></path>
</g>
</g>
</g>
<polygon class="terminal-frame" points="93.8 63.3 284.1 73 335.9 230.5 146.2 197.6 93.8 63.3"></polygon>
<g class="terminal-code">
<line x1="260.2" y1="92.3" x2="212.2" y2="88.7" style="stroke-dashoffset: 0; stroke-dasharray: none;"></line>
<line x1="197.3" y1="87.5" x2="145.2" y2="83.5" style="stroke-dashoffset: 0; stroke-dasharray: none;"></line>
<line x1="251" y1="104.2" x2="223.4" y2="101.8" style="stroke-dashoffset: 0; stroke-dasharray: none;"></line>
<line x1="209.4" y1="100.5" x2="154.4" y2="95.6" style="stroke-dashoffset: 0; stroke-dasharray: none;"></line>
<line x1="256.4" y1="117.9" x2="227.5" y2="114.7" style="stroke-dashoffset: 0; stroke-dasharray: none;"></line>
<line x1="215.9" y1="113.4" x2="183.5" y2="109.8" style="stroke-dashoffset: 0; stroke-dasharray: none;"></line>
<line x1="169.1" y1="108.2" x2="142.9" y2="105.3" style="stroke-dashoffset: 0; stroke-dasharray: none;"></line>
<line x1="275.4" y1="132.8" x2="249.4" y2="129.6" style="stroke-dashoffset: 0; stroke-dasharray: none;"></line>
<line x1="234.4" y1="127.8" x2="197.3" y2="123.3" style="stroke-dashoffset: 0; stroke-dasharray: none;"></line>
<line x1="185.6" y1="121.9" x2="149.1" y2="117.5" style="stroke-dashoffset: 0; stroke-dasharray: none;"></line>
<line x1="261" y1="144.6" x2="244.5" y2="142.5" style="stroke-dashoffset: 0; stroke-dasharray: none;"></line>
<line x1="235.5" y1="141.3" x2="214.9" y2="138.7" style="stroke-dashoffset: 0; stroke-dasharray: none;"></line>
<line x1="203.4" y1="137.2" x2="180.4" y2="134.3" style="stroke-dashoffset: 0; stroke-dasharray: none;"></line>
<line x1="169.3" y1="132.9" x2="155.1" y2="131.1" style="stroke-dashoffset: 0; stroke-dasharray: 15.3136px, 25.3136px;"></line>
<line x1="264.7" y1="158.3" x2="221.9" y2="152.1" style="stroke-dashoffset: 0; stroke-dasharray: none;"></line>
<line x1="208.2" y1="150.1" x2="191.7" y2="147.7" style="stroke-dashoffset: 0; stroke-dasharray: none;"></line>
<line x1="291.3" y1="174.3" x2="268.8" y2="170.9" style="stroke-dashoffset: 0; stroke-dasharray: none;"></line>
<line x1="257.8" y1="169.2" x2="226.5" y2="164.4" style="stroke-dashoffset: 24.8261; stroke-dasharray: 32.6659px, 42.6659px;"></line>
<line x1="217.3" y1="163" x2="185" y2="158.1" style="stroke-dashoffset: 34.6696; stroke-dasharray: 0px, 999999px;"></line>
<line x1="173.8" y1="156.4" x2="152.9" y2="153.2" style="stroke-dashoffset: 23.1436; stroke-dasharray: 0px, 999999px;"></line>
<line x1="278.5" y1="185.6" x2="257.3" y2="182.2" style="stroke-dashoffset: 23.4709; stroke-dasharray: 0px, 999999px;"></line>
<line x1="243.8" y1="179.9" x2="230.3" y2="177.7" style="stroke-dashoffset: 15.6781; stroke-dasharray: 0px, 999999px;"></line>
<line x1="216.5" y1="175.8" x2="196.7" y2="172.5" style="stroke-dashoffset: 22.0731; stroke-dasharray: 0px, 999999px;"></line>
<line x2="262.1" y2="196.1" x1="280.5" y1="199.2" style="stroke-dashoffset: 20.6593; stroke-dasharray: 0px, 999999px;"></line>
<line x2="213.8" y2="187.9" x1="251.1" y1="194.2" style="stroke-dashoffset: 39.8283; stroke-dasharray: 0px, 999999px;"></line>
<line x2="180.8" y2="182.3" x1="202.7" y1="186" style="stroke-dashoffset: 24.2104; stroke-dasharray: 0px, 999999px;"></line>
</g>
<polygon class="laptop-cover" points="103.2 263.6 452.1 339 360.8 12.4 2 2 103.2 263.6"></polygon>
<g class="paw paw-left">
<g class="up" style="opacity: 0; visibility: hidden;">
<path d="M586.6,208.8c-.6-2.3-4.2-15.6-17.2-22.2-2.7-1.3-12.8-6.4-23.6-1.8s-14.6,16.5-14.8,18.4c-1.2,9-.7,18.4,2.4,26.1,2.4,6,7.5,17.2,9.7,20.2"></path>
<g class="pads">
<path d="M561.4,194.9a2.7,2.7,0,0,1,3,.5c.4,1-1.4,2.4-2.6,2.2a1.5,1.5,0,0,1-1.1-1.3A1.2,1.2,0,0,1,561.4,194.9Z"></path>
<path d="M550.7,200.4c.4-.5,1.1-1.1,1.7-.8a2,2,0,0,1,.8,2.2c-.3,1.2-1.8,2-2.5,1.5S550.1,201.3,550.7,200.4Z"></path>
<path d="M541.1,211.1c.5-.4,2.7-.4,3.2.5s-.6,1.8-1.5,1.9S540.4,211.6,541.1,211.1Z"></path>
<path d="M560.6,209.2c2.3-.9,6.4,6.3,7.6,9s-5.3,4.5-7.4,6-5.1-6-5.9-8.3S557.9,210.4,560.6,209.2Z"></path>
</g>
</g>
<path class="down" d="M534.1,231.4c-19.7,6-32.9,18.4-34.2,29.1a30.1,30.1,0,0,0,1.7,14.1,24.8,24.8,0,0,0,6.1,8.8c6,5.1,16.8,4,38-3.9a288.7,288.7,0,0,0,46.5-22.1" style="opacity: 1; visibility: inherit;"></path>
</g>
<g class="headphone headphone-left">
<g class="speaker">
<path d="M609.5,137.3c-17.1,6.3-20.7,51.4-4.5,67.3,1.4,1.5,5.5,5.5,11.3,5.9,8.2.5,14.5-6.3,16.9-8.9,10.1-11,11.5-27.5,8.1-40.1-1.4-4.8-3.9-14-12.7-19.9C627.4,140.8,617.7,134.3,609.5,137.3Z"></path>
<path d="M626.5,196.1c2.7-.4,5.9-2.6,9.3-6,6.6-6.6,6.8-16.6,5.8-24s-4.2-16.1-11.3-19.7a18.7,18.7,0,0,0-10.9-1.9C614,149.3,615.3,192.6,626.5,196.1Z"></path>
<path d="M631.6,151c-4.5,3.3-.5,27.1,3.8,28.2s6.9-6.6,6.2-13.1S637.4,153.5,631.6,151Z"></path>
</g>
<path class="band" d="M638.9,157.7c-4-16.8-25.9-61.9-75.3-95.3A155.5,155.5,0,0,0,515,40.6"></path>
</g>
<g class="music music-left">
<g class="note" style="transform-origin: 0px 0px 0px; opacity: 0; visibility: hidden; stroke: rgb(255, 204, 129);" data-svg-origin="615.699951171875 119.9000015258789" transform="matrix(0.95106,0.30902,-0.30902,0.95106,110.18385,-404.39569)">
<g>
<path d="M633.3,119.9c.6,2,1.3,3.5,3.8,6.3s5.2,4.3,6.5,7.2a6.9,6.9,0,0,1,.7,1.9,10.2,10.2,0,0,1-.7,6.6"></path>
<path d="M633.3,119.9a23,23,0,0,0,2.4,11.7c2.4,4.3,5.1,5.4,6.8,9.5a16.9,16.9,0,0,1,.5,11"></path>
<line x1="633.3" y1="121.1" x2="633.3" y2="166.2"></line>
<path d="M633.3,166.2c.2-3.2-4.6-6.3-8.9-6.3s-8.7,2.6-8.7,5.7,4.7,5.7,8.7,5.8S633.1,169.2,633.3,166.2Z"></path>
</g>
<g>
<path d="M633.3,119.9c.6,2,1.3,3.5,3.8,6.3s5.2,4.3,6.5,7.2a6.9,6.9,0,0,1,.7,1.9,10.2,10.2,0,0,1-.7,6.6"></path>
<path d="M633.3,119.9a23,23,0,0,0,2.4,11.7c2.4,4.3,5.1,5.4,6.8,9.5a16.9,16.9,0,0,1,.5,11"></path>
<line x1="633.3" y1="121.1" x2="633.3" y2="166.2"></line>
<path d="M633.3,166.2c.2-3.2-4.6-6.3-8.9-6.3s-8.7,2.6-8.7,5.7,4.7,5.7,8.7,5.8S633.1,169.2,633.3,166.2Z"></path>
</g>
</g>
<g class="note" style="transform-origin: 0px 0px 0px; opacity: 1; visibility: inherit; stroke: rgb(255, 204, 129);" data-svg-origin="597.3999633789062 116.80000305175781" transform="matrix(0,0,0,0,606.39996,116.8)">
<g>
<polyline points="614.8 155 614.8 116.8 647.5 124 647.5 162.9"></polyline>
<path d="M614.8,155.7c0-3.1-4.4-5.7-8.2-5.9s-9.2,2.8-9.2,6,4.7,5.6,8.7,5.6S614.8,158.8,614.8,155.7Z"></path>
<path d="M647.5,163.3c.1-3.1-4.4-5.7-8.2-5.9s-9.2,2.8-9.1,6,4.7,5.7,8.6,5.7S647.5,166.5,647.5,163.3Z"></path>
</g>
<g>
<polyline points="614.8 155 614.8 116.8 647.5 124 647.5 162.9"></polyline>
<path d="M614.8,155.7c0-3.1-4.4-5.7-8.2-5.9s-9.2,2.8-9.2,6,4.7,5.6,8.7,5.6S614.8,158.8,614.8,155.7Z"></path>
<path d="M647.5,163.3c.1-3.1-4.4-5.7-8.2-5.9s-9.2,2.8-9.1,6,4.7,5.7,8.6,5.7S647.5,166.5,647.5,163.3Z"></path>
</g>
</g>
<g class="note" style="transform-origin: 0px 0px 0px; opacity: 0.704; visibility: inherit; stroke: rgb(86, 156, 250);" data-svg-origin="595.7986450195312 109.4000015258789" transform="matrix(0.2934,-0.03915,0.03915,0.2934,448.02831,35.50756)">
<polyline points="646.5 148.5 646.5 109.4 613.2 117.4 613.2 157.2"></polyline>
<path d="M646.5,149c0-3.1-4.4-5.7-8.1-5.8s-9.2,2.7-9.1,5.9,4.7,5.6,8.6,5.6S646.5,152.1,646.5,149Z"></path>
<path d="M613.2,156.7c.1-3.1-4.4-5.7-8.2-5.8s-9.3,2.7-9.2,6,4.7,5.6,8.7,5.6S613.2,159.9,613.2,156.7Z"></path>
<line x1="613.2" y1="123.2" x2="646.5" y2="115.1"></line>
<line x1="613.2" y1="129.4" x2="646.5" y2="121.8"></line>
</g>
<g class="note" style="transform-origin: 0px 0px 0px; opacity: 0.6409; visibility: inherit; stroke: rgb(126, 209, 226);" data-svg-origin="619.0999755859375 106.5999984741211" transform="matrix(0.35909,0.00287,-0.00287,0.35909,422.76731,-7.07441)">
<g>
<path d="M636.6,152.9c0-3.2-4.4-5.8-8.2-5.9s-9.3,2.8-9.3,6,4.8,5.7,8.7,5.7S636.6,156.1,636.6,152.9Z"></path>
<line x1="636.6" y1="152.9" x2="636.6" y2="106.6"></line>
<path d="M636.6,106.8a33.2,33.2,0,0,0,3.6,7.8c3.8,5.7,7.6,6.9,8.9,11.5a13.3,13.3,0,0,1-.9,8.4"></path>
</g>
<g>
<path d="M636.6,152.9c0-3.2-4.4-5.8-8.2-5.9s-9.3,2.8-9.3,6,4.8,5.7,8.7,5.7S636.6,156.1,636.6,152.9Z"></path>
<line x1="636.6" y1="152.9" x2="636.6" y2="106.6"></line>
<path d="M636.6,106.8a33.2,33.2,0,0,0,3.6,7.8c3.8,5.7,7.6,6.9,8.9,11.5a13.3,13.3,0,0,1-.9,8.4"></path>
</g>
</g>
<g class="note" style="transform-origin: 0px 0px 0px; opacity: 0; visibility: hidden; stroke: rgb(86, 156, 250);" data-svg-origin="615.699951171875 119.9000015258789" transform="matrix(0.46947,-0.88295,0.88295,0.46947,248.78159,402.24282)">
<g>
<path d="M633.3,119.9c.6,2,1.3,3.5,3.8,6.3s5.2,4.3,6.5,7.2a6.9,6.9,0,0,1,.7,1.9,10.2,10.2,0,0,1-.7,6.6"></path>
<path d="M633.3,119.9a23,23,0,0,0,2.4,11.7c2.4,4.3,5.1,5.4,6.8,9.5a16.9,16.9,0,0,1,.5,11"></path>
<line x1="633.3" y1="121.1" x2="633.3" y2="166.2"></line>
<path d="M633.3,166.2c.2-3.2-4.6-6.3-8.9-6.3s-8.7,2.6-8.7,5.7,4.7,5.7,8.7,5.8S633.1,169.2,633.3,166.2Z"></path>
</g>
<g>
<path d="M633.3,119.9c.6,2,1.3,3.5,3.8,6.3s5.2,4.3,6.5,7.2a6.9,6.9,0,0,1,.7,1.9,10.2,10.2,0,0,1-.7,6.6"></path>
<path d="M633.3,119.9a23,23,0,0,0,2.4,11.7c2.4,4.3,5.1,5.4,6.8,9.5a16.9,16.9,0,0,1,.5,11"></path>
<line x1="633.3" y1="121.1" x2="633.3" y2="166.2"></line>
<path d="M633.3,166.2c.2-3.2-4.6-6.3-8.9-6.3s-8.7,2.6-8.7,5.7,4.7,5.7,8.7,5.8S633.1,169.2,633.3,166.2Z"></path>
</g>
</g><g class="note" style="transform-origin: 0px 0px 0px; opacity: 1; visibility: inherit; stroke: rgb(165, 234, 155);" data-svg-origin="615.699951171875 119.9000015258789" transform="matrix(0,0,0,0,634.69995,119.9)">
<g>
<path d="M633.3,119.9c.6,2,1.3,3.5,3.8,6.3s5.2,4.3,6.5,7.2a6.9,6.9,0,0,1,.7,1.9,10.2,10.2,0,0,1-.7,6.6"></path>
<path d="M633.3,119.9a23,23,0,0,0,2.4,11.7c2.4,4.3,5.1,5.4,6.8,9.5a16.9,16.9,0,0,1,.5,11"></path>
<line x1="633.3" y1="121.1" x2="633.3" y2="166.2"></line>
<path d="M633.3,166.2c.2-3.2-4.6-6.3-8.9-6.3s-8.7,2.6-8.7,5.7,4.7,5.7,8.7,5.8S633.1,169.2,633.3,166.2Z"></path>
</g>
<g>
<path d="M633.3,119.9c.6,2,1.3,3.5,3.8,6.3s5.2,4.3,6.5,7.2a6.9,6.9,0,0,1,.7,1.9,10.2,10.2,0,0,1-.7,6.6"></path>
<path d="M633.3,119.9a23,23,0,0,0,2.4,11.7c2.4,4.3,5.1,5.4,6.8,9.5a16.9,16.9,0,0,1,.5,11"></path>
<line x1="633.3" y1="121.1" x2="633.3" y2="166.2"></line>
<path d="M633.3,166.2c.2-3.2-4.6-6.3-8.9-6.3s-8.7,2.6-8.7,5.7,4.7,5.7,8.7,5.8S633.1,169.2,633.3,166.2Z"></path>
</g>
</g><g class="note" style="transform-origin: 0px 0px 0px; opacity: 0; visibility: hidden; stroke: rgb(163, 164, 236);" data-svg-origin="597.3999633789062 116.80000305175781" transform="matrix(0.99756,-0.06976,0.06976,0.99756,49.30969,-178.04039)">
<g>
<polyline points="614.8 155 614.8 116.8 647.5 124 647.5 162.9"></polyline>
<path d="M614.8,155.7c0-3.1-4.4-5.7-8.2-5.9s-9.2,2.8-9.2,6,4.7,5.6,8.7,5.6S614.8,158.8,614.8,155.7Z"></path>
<path d="M647.5,163.3c.1-3.1-4.4-5.7-8.2-5.9s-9.2,2.8-9.1,6,4.7,5.7,8.6,5.7S647.5,166.5,647.5,163.3Z"></path>
</g>
<g>
<polyline points="614.8 155 614.8 116.8 647.5 124 647.5 162.9"></polyline>
<path d="M614.8,155.7c0-3.1-4.4-5.7-8.2-5.9s-9.2,2.8-9.2,6,4.7,5.6,8.7,5.6S614.8,158.8,614.8,155.7Z"></path>
<path d="M647.5,163.3c.1-3.1-4.4-5.7-8.2-5.9s-9.2,2.8-9.1,6,4.7,5.7,8.6,5.7S647.5,166.5,647.5,163.3Z"></path>
</g>
</g><g class="note" style="transform-origin: 0px 0px 0px; opacity: 0; visibility: hidden; stroke: rgb(255, 204, 129);" data-svg-origin="597.3999633789062 116.80000305175781" transform="matrix(0.54464,0.83867,-0.83867,0.54464,411.98871,-667.83538)">
<g>
<polyline points="614.8 155 614.8 116.8 647.5 124 647.5 162.9"></polyline>
<path d="M614.8,155.7c0-3.1-4.4-5.7-8.2-5.9s-9.2,2.8-9.2,6,4.7,5.6,8.7,5.6S614.8,158.8,614.8,155.7Z"></path>
<path d="M647.5,163.3c.1-3.1-4.4-5.7-8.2-5.9s-9.2,2.8-9.1,6,4.7,5.7,8.6,5.7S647.5,166.5,647.5,163.3Z"></path>
</g>
<g>
<polyline points="614.8 155 614.8 116.8 647.5 124 647.5 162.9"></polyline>
<path d="M614.8,155.7c0-3.1-4.4-5.7-8.2-5.9s-9.2,2.8-9.2,6,4.7,5.6,8.7,5.6S614.8,158.8,614.8,155.7Z"></path>
<path d="M647.5,163.3c.1-3.1-4.4-5.7-8.2-5.9s-9.2,2.8-9.1,6,4.7,5.7,8.6,5.7S647.5,166.5,647.5,163.3Z"></path>
</g>
</g><g class="note" style="transform-origin: 0px 0px 0px; opacity: 0.4477; visibility: inherit; stroke: rgb(255, 204, 129);" data-svg-origin="595.7986450195312 109.4000015258789" transform="matrix(0.5425,0.10357,-0.10357,0.5425,316.76354,-133.17006)">
<polyline points="646.5 148.5 646.5 109.4 613.2 117.4 613.2 157.2"></polyline>
<path d="M646.5,149c0-3.1-4.4-5.7-8.1-5.8s-9.2,2.7-9.1,5.9,4.7,5.6,8.6,5.6S646.5,152.1,646.5,149Z"></path>
<path d="M613.2,156.7c.1-3.1-4.4-5.7-8.2-5.8s-9.3,2.7-9.2,6,4.7,5.6,8.7,5.6S613.2,159.9,613.2,156.7Z"></path>
<line x1="613.2" y1="123.2" x2="646.5" y2="115.1"></line>
<line x1="613.2" y1="129.4" x2="646.5" y2="121.8"></line>
</g><g class="note" style="transform-origin: 0px 0px 0px; opacity: 1; visibility: inherit; stroke: rgb(165, 234, 155);" data-svg-origin="595.7986450195312 109.4000015258789" transform="matrix(0,0,0,0,577.79865,109.4)">
<polyline points="646.5 148.5 646.5 109.4 613.2 117.4 613.2 157.2"></polyline>
<path d="M646.5,149c0-3.1-4.4-5.7-8.1-5.8s-9.2,2.7-9.1,5.9,4.7,5.6,8.6,5.6S646.5,152.1,646.5,149Z"></path>
<path d="M613.2,156.7c.1-3.1-4.4-5.7-8.2-5.8s-9.3,2.7-9.2,6,4.7,5.6,8.7,5.6S613.2,159.9,613.2,156.7Z"></path>
<line x1="613.2" y1="123.2" x2="646.5" y2="115.1"></line>
<line x1="613.2" y1="129.4" x2="646.5" y2="121.8"></line>
</g><g class="note" style="transform-origin: 0px 0px 0px; opacity: 0.8959; visibility: inherit; stroke: rgb(165, 234, 155);" data-svg-origin="619.0999755859375 106.5999984741211" transform="matrix(0.08334,0.06238,-0.06238,0.08334,556.56919,37.7478)">
<g>
<path d="M636.6,152.9c0-3.2-4.4-5.8-8.2-5.9s-9.3,2.8-9.3,6,4.8,5.7,8.7,5.7S636.6,156.1,636.6,152.9Z"></path>
<line x1="636.6" y1="152.9" x2="636.6" y2="106.6"></line>
<path d="M636.6,106.8a33.2,33.2,0,0,0,3.6,7.8c3.8,5.7,7.6,6.9,8.9,11.5a13.3,13.3,0,0,1-.9,8.4"></path>
</g>
<g>
<path d="M636.6,152.9c0-3.2-4.4-5.8-8.2-5.9s-9.3,2.8-9.3,6,4.8,5.7,8.7,5.7S636.6,156.1,636.6,152.9Z"></path>
<line x1="636.6" y1="152.9" x2="636.6" y2="106.6"></line>
<path d="M636.6,106.8a33.2,33.2,0,0,0,3.6,7.8c3.8,5.7,7.6,6.9,8.9,11.5a13.3,13.3,0,0,1-.9,8.4"></path>
</g>
</g><g class="note" style="transform-origin: 0px 0px 0px; opacity: 1; visibility: inherit; stroke: rgb(253, 124, 110);" data-svg-origin="619.0999755859375 106.5999984741211" transform="matrix(0,0,0,0,616.09998,106.6)">
<g>
<path d="M636.6,152.9c0-3.2-4.4-5.8-8.2-5.9s-9.3,2.8-9.3,6,4.8,5.7,8.7,5.7S636.6,156.1,636.6,152.9Z"></path>
<line x1="636.6" y1="152.9" x2="636.6" y2="106.6"></line>
<path d="M636.6,106.8a33.2,33.2,0,0,0,3.6,7.8c3.8,5.7,7.6,6.9,8.9,11.5a13.3,13.3,0,0,1-.9,8.4"></path>
</g>
<g>
<path d="M636.6,152.9c0-3.2-4.4-5.8-8.2-5.9s-9.3,2.8-9.3,6,4.8,5.7,8.7,5.7S636.6,156.1,636.6,152.9Z"></path>
<line x1="636.6" y1="152.9" x2="636.6" y2="106.6"></line>
<path d="M636.6,106.8a33.2,33.2,0,0,0,3.6,7.8c3.8,5.7,7.6,6.9,8.9,11.5a13.3,13.3,0,0,1-.9,8.4"></path>
</g>
</g></g>
</g>
</svg>
</div>
<script src="https://static.codepen.io/assets/common/stopExecutionOnTimeout-157cd5b220a5c80d4ff8e0e70ac069bffd87a61252088146915e8726e5d9f147.js"></script>
<script src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/16327/gsap-latest-beta.min.js"></script>
<script src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/16327/DrawSVGPlugin3.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/lodash.js/4.17.15/lodash.min.js"></script>
<script id="rendered-js">
// Inspired By
// https://codepen.io/abeatrize/pen/LJqYey

// Bongo Cat originally created by @StrayRogue and @DitzyFlama

const ID = "bongo-cat";
const s = selector => `#${ID} ${selector}`;
const notes = document.querySelectorAll(".note");

for (let note of notes) {
  note.parentElement.appendChild(note.cloneNode(true));
  note.parentElement.appendChild(note.cloneNode(true));
}

const music = { note: s(".music .note") };
const terminal = { frame: s(".terminal-frame"), code: s(".terminal-code line") };
const cat = {
  pawRight: {
    up: s(".paw-right .up"),
    down: s(".paw-right .down") },

  pawLeft: {
    up: s(".paw-left .up"),
    down: s(".paw-left .down") } };



const style = getComputedStyle(document.documentElement);

const green = style.getPropertyValue("--green");
const pink = style.getPropertyValue("--pink");
const blue = style.getPropertyValue("--blue");
const orange = style.getPropertyValue("--orange");
const cyan = style.getPropertyValue("--cyan");

gsap.set(music.note, { scale: 0, autoAlpha: 1 });

const animatePawState = (selector) =>
gsap.fromTo(
selector,
{ autoAlpha: 0 },
{
  autoAlpha: 1,
  duration: 0.01,
  repeatDelay: 0.19,
  yoyo: true,
  repeat: -1 });



const tl = gsap.timeline();

tl.
add(animatePawState(cat.pawLeft.up), "start").
add(animatePawState(cat.pawRight.down), "start").
add(animatePawState(cat.pawLeft.down), "start+=0.19").
add(animatePawState(cat.pawRight.up), "start+=0.19").
timeScale(1.6);

gsap.from(".terminal-code line", {
  drawSVG: "0%",
  duration: 0.1,
  stagger: 0.1,
  ease: 'none',
  repeat: -1 });


const noteEls = gsap.utils.pipe(
gsap.utils.toArray,
gsap.utils.shuffle)(
music.note);

const numNotes = noteEls.length / 3;
const notesG1 = noteEls.splice(0, numNotes);
const notesG2 = noteEls.splice(0, numNotes);
const notesG3 = noteEls;

const colorizer = gsap.utils.random([green, pink, blue, orange, cyan, "#a3a4ec", "#67b5c0", "#fd7c6e"], true);
const rotator = gsap.utils.random(-50, 50, 1, true);
const dir = amt => `${gsap.utils.random(["-", "+"])}=${amt}`;

const animateNotes = els => {
  els.forEach(el => {
    gsap.set(el, {
      stroke: colorizer(),
      rotation: rotator(),
      x: gsap.utils.random(-25, 25, 1) });

  });

  return gsap.fromTo(els, {
    autoAlpha: 1,
    y: 0,
    scale: 0 },
  {
    duration: 2,
    autoAlpha: 0,
    scale: 1,
    ease: "none",
    stagger: {
      from: "random",
      each: 0.5 },

    rotation: dir(gsap.utils.random(20, 30, 1)),
    x: dir(gsap.utils.random(40, 60, 1)),
    y: gsap.utils.random(-200, -220, 1),
    onComplete: () => animateNotes(els) });

};

tl.
add(animateNotes(notesG1)).
add(animateNotes(notesG2), ">0.05").
add(animateNotes(notesG3), ">0.25");
//# sourceURL=pen.js
    </script>


</body></html>
