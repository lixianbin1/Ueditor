Get Started
=====

> 目前[原项目](https://github.com/fex-team/ueditor)已停止维护，并且关闭了 ISSUE。已存在的问题，可以参阅常见问题的 [FAQ Wiki](https://github.com/fex-team/ueditor/wiki/FAQ)。

## ueditor富文本编辑器介绍

UEditor是由百度web前端研发部开发所见即所得富文本web编辑器，具有轻量，可定制，注重用户体验等特点，开源基于MIT协议，允许自由使用和修改代码。

## 入门部署和体验

### 下载仓库并自己构建

 - 1 `git clone ` 仓库
 - 2 `npm install` 安装依赖（如果没有安装 grunt , 请先在全局安装 grunt）
 - 2.1 `npm install -g grunt-cli` 安装 grunt
 - 3 在终端执行 `grunt default`

### 原生项目使用示例

```html
<!DOCTYPE HTML>
<html lang="en-US">
<head>
	<meta charset="UTF-8">
	<title>ueditor demo</title>
</head>
<body>
	<!-- 加载编辑器的容器 -->
	<script id="container" name="content" type="text/plain">这里写你的初始化内容</script>
	<!-- 配置文件 -->
	<script type="text/javascript" src="ueditor.config.js"></script>
	<!-- 编辑器源码文件 -->
	<script type="text/javascript" src="ueditor.all.js"></script>
	<!-- 实例化编辑器 -->
	<script type="text/javascript">
	    var ue = UE.getEditor('container');
	</script>
</body>
</html>
```

配置项也可以通过ueditor.config.js文件修改，具体的配置方法请看文档说明

## 相关文档

ueditor 文档: [http://fex-team.github.io/ueditor/](http://fex-team.github.io/ueditor/ '文档')

ueditor 官网：[http://ueditor.baidu.com](http://ueditor.baidu.com "ueditor 官网")

ueditor API 文档：[http://ueditor.baidu.com/doc](http://ueditor.baidu.com/doc "ueditor API 文档")

ueditor github 地址：[http://github.com/fex-team/ueditor](http://github.com/fex-team/ueditor "ueditor github 地址")

ueditor 第三方插件贡献 wiki : [第三方插件贡献规范](http://ueditor.baidu.com/website/thirdproject.html)

ueditor 贡献代码规范（javascript）： [javascript规范](https://github.com/fex-team/styleguide/blob/master/javascript.md)