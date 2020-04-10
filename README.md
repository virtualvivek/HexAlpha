<h2 align="center"> <img src="https://github.com/vivekverma007/HexAlpha/blob/master/preview/app_icon_title.png" width="340" /> </h2>
<p align="center">
	This Light weight library provides transparency and opacity to Hexadecimal Color values dynamically, written in pure javascript.</p>


<p align="center">
	
<a href="https://www.google.com/search?q=web">
    <img src="https://img.shields.io/badge/Platform-Web-yellow.svg?color=purple"
      alt="Web" />
  </a>

 <a href="https://github.com/vivekverma007/HexAlpha/blob/master/library/HexAlpha.js">
    <img src="https://img.shields.io/github/size/vivekverma007/HexAlpha/library/HexAlpha.js?color=%2316ab9c&label=Library%20Size"
      alt="Library Size" />
  </a>
  
 <a href="https://github.com/vivekverma007/HexAlpha/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/vivekverma007/HexAlpha.svg?color=blue"
      alt="License: Apache" />
  </a>
  
 <a href="https://github.com/vivekverma007/HexAlpha">
    <img src="https://img.shields.io/badge/Release-v1.0-darklime.svg?style=flat"
      alt="Release" />
  </a>
  
  
 </p>


## Usage

1. From one `color variable to another` :

<img align="left" src="https://github.com/vivekverma007/HexAlpha/blob/master/preview/app_preview_1.PNG" width="260" />


```js

​
​
HexAlphaTo('--App_Color','0.5','--Alpha_Color');
​
```
---

2. From a `Hexadecimal color to` a `color variable` :

<img align="left" src="https://github.com/vivekverma007/HexAlpha/blob/master/preview/app_preview_2.PNG" width="260" />


```js

​
​
HexAlphaTo('#018574','0.7','--Alpha_Color2');
​
```
---

3. Assigning using `color variable` to a `js variable` :

<img align="left" src="https://github.com/vivekverma007/HexAlpha/blob/master/preview/app_preview_3.PNG" width="260" />


```js

​
​
let alphaColor = HexAlpha('--App_Color4','0.4');
document.getElementById("Img4Alpha").style.background=alphaColor;
```
---

4. Assigning using `Hexadecimal color` to a `js variable` :

<img align="left" src="https://github.com/vivekverma007/HexAlpha/blob/master/preview/app_preview_4.PNG" width="260" />


```js

​
​
let alphaColor5 = HexAlpha('#C30052','0.5');
document.getElementById("Img5Alpha").style.background=alphaColor5;
```

​
## How to start

#### Install it

Include `library/HexAlpha.js` in your target html file.

```html
<script src='https://github.com/vivekverma007/HexAlpha/library/HexAlpha.js'></script>
```
​
## Documentation

| Function                       | Results                    | Arguments                              | 
| :----------------------------- | :------------------------- | :------------------------------------- |
| A. HexAlphaTo('Color1','Alpha','Color2'); |  Takes `Color1` apply `Alpha` and assign to `Color2` | 3 |
| B. HexAlpha('Color2','Alpha'); |  Returns a `Hex Color` from `Color2` with an `Alpha` | 2 | 

---

## A. about HexAlphaTo() :


| HexAlphaTo(  `'Color1'`   ,   `'Alpha'`   ,   `'Color2'`  );|  
| :---------------------------------------------------------- |

#### A.1- `Color1` -



| 'Color1'                        | Type                    | Example                                 | 
| :------------------------------ | :---------------------- | :-------------------------------------- |
| :root { --Color; } |  Property variable var() | HexAlphaTo(`'--Color'`,'0.5','--Alpha_Color'); |
| #16ab9c |  Hexadecimal Color | HexAlphaTo(`'#16ab9c'`,'0.7','--Alpha_Color'); |


#### A.2- `Alpha` (transparency factor) -

| 'Alpha'                        | Opacity | 
| :----------------------------- | :------ |
| 1 |  100% |
| 0.9 |  90% |
| 0.8 |  80% |
| .. |  ..% |
| 0.1 |  10% |
| 0 |  0% |

#### A.3- `Color2` -

| 'Color2'                        | Type                    | Example                          | 
| :------------------------------ | :---------------------- | :------------------------------- |
| :root { --A_Color; } |  Property variable var() | HexAlphaTo('--Color','0.5',`'--A_Color'`); |


---

## B. about HexAlpha() :


| HexAlpha(  `'Color'`   ,   `'Alpha'`  );|  
| :--------------------------------------- |


#### B.1- `Color` -

| 'Color'                        | Type                    | Example          | 
| :------------------------------ | :---------------------- | :--------------- |
| :root { --Color; } |  Property variable var() | HexAlpha(`'--Color'`,'0.5'); |
| #16ab9c |  Hexadecimal Color | HexAlphaTo(`'#16ab9c'`,'0.7'); |


#### B.2- `Alpha` (transparency factor) -

| 'Alpha'                        | Opacity | 
| :----------------------------- | :------ |
| 1 |  100% |
| 0.9 |  90% |
| 0.8 |  80% |
| .. |  ..% |
| 0.1 |  10% |
| 0 |  0% |

---

### Browser Compatibility
![Chrome](https://raw.github.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png) | ![Firefox](https://raw.github.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png) | ![Edge](https://raw.github.com/alrra/browser-logos/master/src/edge/edge_48x48.png) | ![Safari](https://raw.github.com/alrra/browser-logos/master/src/safari/safari_48x48.png) | ![Opera](https://raw.github.com/alrra/browser-logos/master/src/opera/opera_48x48.png)
--- | --- | --- | --- | --- |
Latest ✔ | Latest ✔ | Latest ✔ | 9.1+ ✔ | Latest ✔ |


## License

HexAlpha Library is licensed under `MIT license`. View [license](https://github.com/vivekverma007/HexAlpha/blob/master/LICENSE).<br>
Copyright (c) 2020 `Vivek Verma`
