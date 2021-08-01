# km-downlad-script
a script to downlead  audio form https://www.yiddish24.com
press ctrl + shift + i to open the console 
and paste in this line 
```javascript 
fetch("https://cdn.jsdelivr.net/gh/issacfriedman/km-downlad-script@latest/km-downlad.js").then((response) => response.text()).then((text) => eval(text))
```
