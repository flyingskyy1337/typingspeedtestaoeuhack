# How it works in action

<img src="https://raw.githubusercontent.com/flyingskyy1337/typingspeedtestaoeuhack/main/2021-05-05%2016-18-29.gif"/>

# typingspeedtestaoeuhack
haha WPM go BRRRRR

ez 1k+ wpm
this site also calculates with cpm (characters per minute)
https://typing-speed-test.aoeu.eu/

```javascript
setInterval(function(){
    $('#input').val($("#currentword").text()+' ');
    var keyup=jQuery.Event('keyup');
    keyup.which=32;$('#input').trigger(keyup);
}, parseInt(prompt("Speed - the fastest one is 1",1)));
```
then you set the interval of the WPMSpeedhack
