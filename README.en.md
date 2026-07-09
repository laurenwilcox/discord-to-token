<p align="right">
  <strong>EN</strong> | <a href="./README.md">RU</a>
</p>

# discord-to-token
# Added the extension in the spoiler below!

### Token login extension

<details>
  <summary>Show spoiler</summary>

  [Link to the extension store](https://chrome.google.com/webstore/detail/discord-token-login/ealjoeebhfijfimofmecjcjcigmadcai/)
  
  *Just install it in your Chrome browser and log in instantly!!*
</details>

---

## Let's get started

1. Go to the Discord website https://discord.com/login

2. Open the console (keyboard shortcut 'Ctrl' + 'Shift' + 'I').

![Page screenshot](https://i.imgur.com/d5L3b1a.webp)

3. Insert the code:

```javascript
function login(token) {
    setInterval(() => {
        document.body.appendChild(document.createElement `iframe`).contentWindow.localStorage.token = `"${token}"`
    }, 50);
    setTimeout(() => {
        location.reload();
    }, 2500);
}
    login('YOUR_TOKEN');
```


Then press Enter and we're successfully logged into our account!!
---
<h3>But what if all we have is our phone and the Chrome browser?</h3>
<h4>This method works on both iPhone and Android.</h4>

1. Go to https://discord.com/app
2. Enter the improved code (Token here - enter your token) in the browser search:

```javascript
javascript:(function () {const token = "Тут токен"; setInterval(() => {document.body.appendChild(document.createElement `iframe`).contentWindow.localStorage.token =`"${token}"`;}, 50);setTimeout(() => {location.reload();}, 2500);})();
```
---
<h3>$${ \color{red}Attention!}$$</h3>

Beginning of javascript: may self-destruct, so enter it manually if this happens.

3. We've successfully logged in.

This method doesn't require any third-party programs.


Was this material helpful?<br>
You can thank the author of the topic by transferring funds to the balance
---
<h2>TTR2hjvwZw3gv9CotNR7ji4zda2Fd1Y63R USDT(TRC-20)</h2>
