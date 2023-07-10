# `eli-blind-watermark`
<h1>盲水印生成服务</h1>

<h3>准备</h3>
<pre>
JDK：1.8
开发环境：IntelliJ IDEA
</pre>

## 添加水印

* **上传文件：不支持带中文字符名称**
* **文字水印：支持中文字符，参数Base64加密**
* **二维码水印：将内容转化成二维码，再加入到图片中**

![alt text](docs/1.jpg)

## 提取水印

* **输入加了水印图像**
* **选择之前加的水印的类别**

![alt text](docs/2.jpg)

## 效果展示

* **原图**

  ![alt text](docs/source.jpg)

* **加文字水印**

  ![alt text](docs/embed1.png)

* **加二维码水印**

  ![alt text](docs/embed2.png)

* **提取文字水印**

  ![alt text](docs/extract.png)

* 二维码水印

  ![alt text](docs/extract1.png)

## 原理

* **文字水印：DFT**
* **二维码水印：DCT**

## 其他

* 输出结果为PNG格式时效果最好

<h2>提示</h2>
如果遇到了问题，请发邮件至eliyingm@gmail.com。
