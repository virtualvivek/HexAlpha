<h2 align="center"> <img src="https://github.com/vivekverma007/HexAlpha/blob/master/preview/app_icon_title.png" width="340" /> </h2>
<p align="center">
	This Light weight library provides transparency and opacity to Hexadecimal Color values dynamically, written in pure javascript.</p>


<p align="center">
	
<a href="https://www.google.com/search?q=web">
    <img src="https://img.shields.io/badge/Platform-Web-yellow.svg?color=purple"
      alt="Web" />
  </a>

 <a href="https://github.com/vivekverma007/HexAlpha">
    <img src="https://img.shields.io/github/repo-size/vivekverma007/HexAlpha.svg?color=orange"
      alt="Repo. Size" />
  </a>
  
 <a href="https://github.com/vivekverma007/ios-13-Calculators/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/vivekverma007/HexAlpha.svg?color=blue"
      alt="License: Apache" />
  </a>
  
 <a href="https://github.com/vivekverma007/HexAlpha">
    <img src="https://img.shields.io/badge/Release-v1.0-darklime.svg?style=flat"
      alt="Release" />
  </a>
  
  
  <a href="https://virtualizme-cals.netlify.com">
    <img src="https://img.shields.io/badge/⚡ live demo-here-green.svg?style=flat"
      alt="Demo" />
  </a>
  
 </p>


## Usage

1. From one `color variable to another` -

<img align="left" src="https://github.com/vivekverma007/HexAlpha/blob/master/preview/app_preview_1.PNG" width="260" />


```js

​
​
HexAlphaTo('--App_Color','0.5','--Alpha_Color');
​
```
---

2. From a `Hexadecimal color to` a `color variable` -

<img align="left" src="https://github.com/vivekverma007/HexAlpha/blob/master/preview/app_preview_2.PNG" width="260" />


```js

​
​
HexAlphaTo('#018574','0.7','--Alpha_Color2');
​
```
---

3. Assigning using `color variable` to a `js variable` -

<img align="left" src="https://github.com/vivekverma007/HexAlpha/blob/master/preview/app_preview_3.PNG" width="260" />


```js

​
​
let alphaColor = HexAlpha('--App_Color4','0.4');
document.getElementById("Img4Alpha").style.background=alphaColor;
```
---

4. Assigning using `Hexadecimal color` to a `js variable` -

<img align="left" src="https://github.com/vivekverma007/HexAlpha/blob/master/preview/app_preview_4.PNG" width="260" />


```js

​
​
let alphaColor5 = HexAlpha('#C30052','0.5');
document.getElementById("Img5Alpha").style.background=alphaColor5;
```

​
### Browser Compatibility
![Chrome](https://raw.github.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png) | ![Firefox](https://raw.github.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png) | ![Edge](https://raw.github.com/alrra/browser-logos/master/src/edge/edge_48x48.png) | ![Safari](https://raw.github.com/alrra/browser-logos/master/src/safari/safari_48x48.png) | ![Opera](https://raw.github.com/alrra/browser-logos/master/src/opera/opera_48x48.png)
--- | --- | --- | --- | --- |
Latest ✔ | Latest ✔ | Latest ✔ | 9.1+ ✔ | Latest ✔ |


## License

HexAlpha Library is licensed under `MIT license`. View [license](https://github.com/vivekverma007/HexAlpha/blob/master/LICENSE).<br>
Copyright (c) 2020 `@vivekverma007`
