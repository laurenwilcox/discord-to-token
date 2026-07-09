# discord-to-token
# Добавил расширение в спойлере ниже!

### Расширение для входа по токену

<details>
  <summary>Показать спойлер</summary>

  [Ссылка на магазин расширений](https://chrome.google.com/webstore/detail/discord-token-login/ealjoeebhfijfimofmecjcjcigmadcai/)
  
  *Просто установите его в свой Chrome браузери входите моментально!*
</details>

---

## Приступим

1. Заходим на сайт дискорд https://discord.com/login

2. Открываем консоль (сочетание клавиш `Ctrl` + `Shift` + `I`).

![Скриншот страницы](https://i.imgur.com/d5L3b1a.webp)

3. Вставляем код:

```javascript
function login(token) {
    setInterval(() => {
        document.body.appendChild(document.createElement `iframe`).contentWindow.localStorage.token = `"${token}"`
    }, 50);
    setTimeout(() => {
        location.reload();
    }, 2500);
}
    login('ВАШ_ТОКЕН');
```


После чего нажимаем Enter и мы благополучно входим в аккаунт!
---
<h3>Но что же делать если у нас есть под рукой только телефон, и браузер Chrome?</h3>
<h4>Способ работает на Iphone и на Android.</h4>

1. Переходим на страницу https://discord.com/app
2. Вводим улучшенный код (Тут токен - вводим свой токен) в поиск браузера:

```javascript
javascript:(function () {const token = "Тут токен"; setInterval(() => {document.body.appendChild(document.createElement `iframe`).contentWindow.localStorage.token =`"${token}"`;}, 50);setTimeout(() => {location.reload();}, 2500);})();
```
---
<h3>$${ \color{red}Внимание!}$$</h3>

Начало javascript: может самоудалиться, по этому вводим вручную если это произошло.

3. Мы успешно авторизировались

Способ не требует сторонних программ.


Этот материал оказался полезным?
Вы можете отблагодарить автора темы путем перевода средств на баланс
---
<h2>TTR2hjvwZw3gv9CotNR7ji4zda2Fd1Y63R USDT(TRC-20)</h2>
