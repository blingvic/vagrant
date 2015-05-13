# 使用vagrant 搭建开发环境
------

### 1. 安装vagrant

[下载vagrant][1]

### 2. vagrantbox 源下载

[get vagrantbox][2]

### 3. install

新建项目目录 project, 同时把下载的box源移入当前目录
命令行进入当前目录


```php
    vagrant box add {title} {url}
```
    title 为这个box的名字，url 是 vagrantbox存放路径

```php
    vagrant init {title}
```
    初始化box

```php
    vagrant up
```
    启动的vagrant

### 4. 远程登录环境
    推荐工具： [putty] [xshell]。

```php
    username  vagrant
    password  vagrant
```



[1]: https://www.vagrantup.com
[2]: http://www.vagrantbox.es/
