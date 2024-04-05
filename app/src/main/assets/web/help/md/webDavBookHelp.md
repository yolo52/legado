# WebDav 书籍简明使用教程

> 本帮助页会在第一次进入时弹出，后续则不再出现，如想查看，请点击右上角 “**⁝**” > 帮助 查看此页。

虽然阅读主要是用来看网络小说的工具，但为了方便书友，也提供了一些本地书籍阅读的简单支持（epub、txt）

但阅读本地书籍的一个难题就是如何在多设备上同步阅读进度以及书籍，假如换了设备之后，原来设备上的本地书籍也要再次手动导入，不太方便。

阅读本身没有自己的服务器，没有类似多看、微信读书那种服务器存储的可能性，但是，阅读支持 WebDav 备份，那么我们也可以利用 WebDav 来同步书籍。

### 前提条件
1. 配置好书籍存储位置（WebDav书籍下载存储到的位置）：依次点击我的/其他设置/书籍存储位置，选择书籍保存位置即可。

2. 配置好 WebDav 备份（WebDav书籍的保存位置）：我的/备份与恢复/WebDav设置。这里需要配置 WebDav 备份的服务器地址、账号、密码。详细的配置方案这里不赘述，请看这篇文章：[坚果云注册与配置 · 语雀 (yuque.com)](https://www.yuque.com/legado/wiki/fkx510) 或点击该页面右上角的帮助按钮，查看配置方法。

### 上传书籍到 WebDav

配置好 WebDav 后，从主界面进入 WebDav 书籍页没有任何书籍显示，这是很正常的，因为我们WebDav的服务器上还没有任何书籍。

目前将书籍上传到 WebDav 的方式有三种：

1. App 上传已导入的本地书籍。

   长按已导入的本地书籍进入书籍详情 > 右上角 “**⁝**” 找到 **上传 WebDav** ，点击，等待几秒后即可上传成功。

2. App 上传已缓存的网络书籍。

   主界面右上角点击更多设置 > 点击缓存/导出，在此页面右上角 “**⁝**” 找到 **导出到 WebDav** 并勾选。那么在书籍导出的时候便会自动上传一份到 WebDav 服务器中。

3. 使用坚果云客户端/自建WebDav服务客户端上传。

   对于大部分用户来说，App上传足够了，但有些用户书籍数量可能比较大，那么我们不建议您一本一本通过 App 上传，更好的方式是使用您所使用的 WebDav 服务的客户端批量上传。

   假设我们使用的坚果云的 WebDav 服务，进入 [坚果云官网](https://www.jianguoyun.com/d/home#/) ,下载对应平台的客户端安装运行，找到文件夹目录 legado/books ，这里就是存放书籍的位置，您可以批量将书籍上传到该文件夹下。

**不管是使用上述的任何一种方式上传的书籍，为了确保上传无误，请您最好在上传书籍后进入 WebDav 书籍页 检查是否能看到已经上传的书籍。**

### 下载 WebDav 书籍到本地

与上传方式的多种多样不同，下载书籍到本地的方式比较朴素。

在 **WebDav 书籍页** 浏览已经上传的书籍，找到自己要下载的书籍，点击 **加入书架** 按钮，软件则会自动下载该书籍到本地并加入到书架中。

### 注意事项

- 如果使用的是坚果云的 WebDav 服务，免费流量限额对于同步App设置等以及 **少量的书籍** 足够了。但是如果是频繁需要上传/下载书籍的用户流量可能就不太够用了，请注意个人的用量，避免出现超出限额影响 App 设置等的同步。

### 常见问题

- 进入 **WebDav书籍页** 提示 "获取WebDav书籍出错 webDav 没有配置"。

  > 这是因为没有配置 WebDav 同步服务，按照上文 前提条件 中提到的配置 Webdav 同步的方法配置好就行了。

- A 设备上传的本地书籍能否在 B 设备上看到，是否能够自动加到书架？

  > 如果 A 设备和 B 设备配置了相同的 WebDav 服务，那么 B 在 **WebDav 书籍页** 就能看到 A 上传的书籍。但是无法直接在书架上看到该书籍，这个可能后续会想方案来做，目前必须自己在 **WebDav 书籍页** 找到该书籍手动点击 **加入书架** 导入才行。

- 本地书籍的阅读进度/书签等是否同步？

  > 可以同步。