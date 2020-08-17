# raj-antispam.js
Discord Botlarınız/Sunucularınız İçin Spam Koruması


## Kurulum
Bu Modül Discord.js Botları İçindir [Discord.js](https://discord.js.org/#/) Discord.js Sitesi.

Bunu yaptıktan sonra, anti spam'i ayarlamak çok kolay olacaktır.
Başlamak için aşağıdaki kodu takip edebilirsiniz!
```js
const koruma = require("raj-antispam.js"),
db = require('quick.db'),


koruma(client, {
  uyarmaSınırı: 2, 
  banlamaSınırı: 3,
  aralık: 2000, 
  uyarmaMesajı: "Hey sen dalgın spamcı, kendini bugün ayık. Yoksa ban gelir.", 
  rolMesajı: "Hakettiğini Buldu!", 
  maxSpamUyarı: 5,
  maxSpamBan: 5, 
  zaman: 5, 
  rolİsim: "susturulmuş" 
});

```

