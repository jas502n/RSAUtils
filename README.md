# loan-application


https://blog.csdn.net/zhchs2012/article/details/79026298

```
原文链接：https://blog.csdn.net/zhchs2012/article/details/79026298

RSA是一种非对称加密算法，简单理解就是两个密钥：一个公钥，一个私钥。
同时它也可以用来签名和验签，正好与加密相反。

加密：公钥加密，私钥解密；
签名：私钥签名，公钥验签。
有意思的是有些人分不清公钥私钥的用处，这里提供一个思路：
用作加密时，密文泄露是无所谓的（相对而言），重要的是用于解密的密钥必须安全，所以用不公开的私钥来解密，用公钥来加密；
用作签名时，目的是防止别人伪造我的身份发信息，所以用私钥来签名，用公钥来验签。

对于加密及签名的讲解，看过一篇很棒的翻译，看完过后非常有助于理解，并且图文并茂，很生动：
http://www.ruanyifeng.com/blog/2011/08/what_is_a_digital_signature.html


```
