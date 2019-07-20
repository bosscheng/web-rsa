# 简介
web端js 使用的 openssl rsa encryption 加密算法


## 使用
```
// AMD

import JSEncrypt from 'web-rsa';
var encrypt = new JSEncrypt();
// encrypt
encrypt.setPublicKey('publish key')
var data = encrypt.encrypt('string');


// decrypt
var decrypt = new JSEncrypt();
decrypt.setPrivateKey('private key');
var data1 = decrypt.decrypt(data);

```

```
// CMD
var JSEncrypt = require('./rsa');
var encrypt = new JSEncrypt();
// encrypt
encrypt.setPublicKey('publish key')
var data = encrypt.encrypt('string');

// decrypt
var decrypt = new JSEncrypt();
decrypt.setPrivateKey('private key');
var data1 = decrypt.decrypt(data);
```

```
// browser
var encrypt = new window.JSEncrypt();

// encrypt
encrypt.setPublicKey('publish key')
var data = encrypt.encrypt('string');

// decrypt
var decrypt = new JSEncrypt();
decrypt.setPrivateKey('private key');
var data1 = decrypt.decrypt(data);
```



