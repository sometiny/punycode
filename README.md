# punycode
Punycode编码/解码的实现。
# 用法
```
const punycode = require('punycode');
console.log(punycode.encode('用法')); //nwwn1p
console.log(punycode.decode('nwwn1p')) //用法

console.log(punycode.toIDN('用法.中国')); //xn--nwwn1p.xn--fiqs8s
console.log(punycode.fromIDN('xn--nwwn1p.xn--fiqs8s')) //用法.中国
```
