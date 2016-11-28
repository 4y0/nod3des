### 3DES 🔐 For FT APIs


`npm install nod3des`

```
//Encryption 
var _3DES = require('nod3des');

//Encryption key = "Tk_ksodk"
//Text to encrypt ==> "SMS"
_3DES.encrypt("Tk_ksodk", "SMS"); //PjBSczoWdA4=
```




```
//Decryption 
var _3DES = require('nod3des');

//Encryption key = "Tk_ksodk"
//Text to decrypt ==> "PjBSczoWdA4="
_3DES.decrypt("Tk_ksodk", "PjBSczoWdA4="); //SMS
```