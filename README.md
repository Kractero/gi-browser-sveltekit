# Hare

**H**umble **A**utomated **R**unner for **E**xecuting NationStates Scripts 

A central repository to running a variety of NationStates in the browser. 

The next step in my endless quest to make NationStates scripts more easy to use. These scripts would commonly have required downloading external dependencies like Python and some knowledge of installing dependencies or the command line in the browser.

If you would like script inclusion, either join the discord and ask or make an issue.

If this tool helped, star the repo or [gift me a leg](https://www.nationstates.net/nation=kractero) (joking, unless...)

This thing definitely needs some kind of dynamic route as besides the typescript logic and some changes to input the pages are largely the same...

All icons were taken from [Icons8](https://icons8.com/icons).

## NOTE

### Preqrequisites
A lot of these userscripts generate an html sheet that almost necessitate the use of an autocloser. There are a lot of varieties but I'd recommend:
```js
// ==UserScript==
// @name         autoclose=1
// @namespace    http://tampermonkey.net/
// @version      0.1
// @description  try to take over the world!
// @author       9003
// @match         *://*/*autoclose=1
// @exclude      https://www.nationstates.net/*page=show_dilemma*
// @icon         https://www.google.com/s2/favicons?sz=64&domain=nationstates.net// 
// @grant        none
// ==/UserScript==

(function() {
    'use strict';
    window.close();
    // Your code here...
})();
```

Others may require different scripts, I have included them on each page.

Most of these sheet-based userscripts require the use of containers. You can use Containerise and generate the rules necessary within the website, but also I want to shill my [Cardtainers](https://addons.mozilla.org/en-US/firefox/addon/cardtainers/), which will automatically create rules that match nations given a puppet list, whether you prefer container or nation.

### Ratelimits
All of these scripts are running using YOUR rate limit. 

AS STATED FROM [HERE](https://www.nationstates.net/pages/api.html):

>The API is rate-limited and will temporarily lock you out if you send too many requests within a short period of time. (And return status 429: "Too Many Requests From Your IP Address.")
>
>API Rate Limit: 50 requests per 30 seconds. 

If you open a new tab to try and run multiple, you will get ratelimited.

<hr>

![Svelte](https://img.shields.io/badge/svelte-%23f1413d.svg?style=for-the-badge&logo=svelte&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)

![Hare](https://static.miraheze.org/bluearchivewiki/4/47/Hare.png?20210217174626)