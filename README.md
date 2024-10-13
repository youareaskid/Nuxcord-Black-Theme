# 🌙ᆞNuxcord-Black-Theme

Bonjour, je vous présente mon nouveau script que j'ai créer pour pouvoir avoir un thème noir sur Discord !

![image](https://github.com/user-attachments/assets/0376e3ea-288f-4596-ac5f-643dfa1b9559)

## ❔ᆞHow To Use

Pour commencer :

1. Ouvrez l'application Discord

2. Attendez que discord est complétement chargé

3 - Faite CTRL + SHIFT + I

4 - Une fois le menu de développeur ouvert rentrer dans la catégorie "Console"

5 - rentrez ce code :

```
(function(){const style=document.createElement('style');style.innerHTML=`:root{--background-primary:#000000!important;--background-secondary:#000000!important;--background-tertiary:#000000!important;--background-accent:#000000!important;--background-faint:#000000!important;--text-normal:#FFFFFF!important;--text-muted:#FFFFFF!important;--interactive-normal:#FFFFFF!important;--interactive-hover:#FFFFFF!important;--interactive-active:#FFFFFF!important;--button-background:#000000!important;--button-border:#000000!important;--button-text:#FFFFFF!important;}body{background-color:#000000!important;}.sidebar-3q9ozD,.content-2p3cIY{background-color:#000000!important;border-color:#000000!important;}button,.button-3cCIVh,.button-2sF7_3{background-color:#000000!important;color:#FFFFFF!important;border:1px solid #000000!important;}.channelName-1h8Jm0,.username-1A5YzC,.role-3g3P1e{color:#FFFFFF!important;}.message-2qnXI6{background-color:#000000!important;color:#FFFFFF!important;}.modal-3P9g5t,.dialog-1A0gjR{background-color:#000000!important;color:#FFFFFF!important;}#nuxcord-text{position:fixed;bottom:20px;left:50%;transform:translateX(-50%);opacity:0.8;font-size:15px;font-weight:bold;color:#000000;z-index:10000;pointer-events:none;font-family:"Helvetica Neue","Arial",sans-serif;text-shadow:0 0 5px #FFFFFF;}`;document.head.appendChild(style);const textElement=document.createElement('div');textElement.id='nuxcord-text';textElement.innerText='Nuxcord';document.body.appendChild(textElement);})();
```

6 - Eh voila vous avez maintenant le Nuxcord-Black-Theme !
