# FileHelper

这个项目我会不断维护，抽取常用但难以实现的各种文件操作。

一人计短，多人计长，也期待你加入贡献的行列。

## 1.读取Resources下的资源

```java

ClassPathResource resource = new ClassPathResource();
String html = resource.readString("commons.html",StandardCharsets.UTF_8);
String htm = resource.readString("commons.htm");
byte[] bytes = resource.readByte("commons.html");
InputStream inputStream = resource.read("commons.html");

```

## 2.读取文件的ContentType

```java
String contentType = ContentType.getContentType("/index.html");
```

## About

Blog：<http://www.yueshutong.cn/>

Email：[yster@foxmail.com](mailto:yster@foxmail.com)

Github：<https://github.com/yueshutong/SnowJena>

Gitee：<https://gitee.com/zyzpp/SnowJena>

交流QQ群：781927207

如果帮助到你了，请不吝赞赏！谢谢！

<img src="http://ww3.sinaimg.cn/large/006tNc79ly1g43096t4oaj30tc0tc41y.jpg" width="300px" referrerpolicy="no-referrer">

<img src="http://ww3.sinaimg.cn/large/006tNc79ly1g4rgr77f3ij308c0au74a.jpg" width="300px" referrerPolicy="no-referrer">
