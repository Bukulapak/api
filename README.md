# API

```js
function GetResponse(result){
    document.getElementById("formsignup").innerHTML = result;
}
let datajson = {
    "namadepan": namadepan,
    "namabelakang": namabelakang,
    "email": email,
    "password": password
    }
postWithToken("https://foo.bar","Token","dsf9ygf87h98u479y98dj0fs89nfd7",datajson,GetResponse);
```
