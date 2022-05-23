# HTTP和HTTPS协议的区别有哪些？

HTTP和HTTPS协议的区别主要有4点：

1. https协议需要到CA申请`证书`。
2. http是超文本传输协议，信息是明文传输；https 则是具有安全性的`ssl加密传输协议`。
3. http和https使用的是完全不同的连接方式，用的端口也不一样，前者是80，后者是`443`。
4. http的连接很简单，是无状态的；HTTPS协议是由`SSL+HTTP协议`构建的可进行`加密传输`、身份认证的网络协议，比http协议安全。