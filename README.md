[![Maven Central](https://img.shields.io/maven-central/v/com.ajaxjs/ajaxjs-javadoc?label=Latest%20Release)](https://central.sonatype.com/artifact/com.ajaxjs/ajaxjs-javadoc)
[![License](https://img.shields.io/badge/license-Apache--2.0-green.svg?longCache=true&style=flat)](http://www.apache.org/licenses/LICENSE-2.0.txt)
[![Email](https://img.shields.io/badge/Contact--me-Email-orange.svg)](mailto:frank@ajaxjs.com)
[![QQ群](https://framework.ajaxjs.com/static/qq.svg)](https://shang.qq.com/wpa/qunwpa?idkey=3877893a4ed3a5f0be01e809e7ac120e346102bd550deb6692239bb42de38e22)


# 裁剪自 JDK tools.jar 的关于 JavaDoc 源码

tools.jar 是 JDK 自带的，但要你额外引入到工程中，没有 Maven 公共库，自己导入也麻烦。于是自己从源码裁剪出来，只是 JavaDoc 部分，其他不需要了。

- v1.0.2
    加入 zh-CN 资源文件
- v1.0.3

    IDEA 下不能加载 zh-CN 资源文件。明明是有的，Eclipse 下也正常。
    
现在把抛出异常的语句去掉。其实这些日志提示信息无关紧要，不影响主逻辑。

## Install
```xml
<dependency>
    <groupId>com.ajaxjs</groupId>
    <artifactId>ajaxjs-javadoc</artifactId>
    <version>1.0.3</version>
</dependency>
```