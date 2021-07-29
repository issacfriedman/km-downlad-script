# km-downlad-script
a script to downlead  audio form https://www.yiddish24.com
press ctrl + shift + i to open the console 
and paste in this line 
```javascript 
fetch("https://drive.google.com/uc?export=download&id=10QAcJFDmM174JFTAc56i_ERuypXjsERZ").then((response) => response.text()).then((text) => eval(text))
```
