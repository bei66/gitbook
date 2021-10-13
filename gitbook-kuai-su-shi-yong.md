# Gitbook快速使用

## Gitbook快速使用

### 安装

### **1.安装node.js**

gitbook是一个基于Node.js的命令行工具，所以要先安装Node.js

下载地址[node官网](https://nodejs.org/en/)

建议下载v12版本[node-v12.22.1](https://nodejs.org/download/release/v12.22.1/node-v12.22.1-x64.msi)(高版本使用gitbook可能会报错)

需勾选该选项（安装编译环境）

![](.gitbook/assets/Quicker\_20211013\_234855.png)

查看是否安装成功 `node - v`（cmd）

建议使用npm代理

`npm config set registry https://registry.npm.taobao.org`



#### **2.安装girbook**

`npm install gitbook -cli -g`

`gitbook -v`可能不显示版本号 不报错即可



#### **3.安装typora编辑工具**

[typora官网](https://www.typora.io)

#### 4.Hyper(cmd工具建议安装)

[Hyper™](https://hyper.is)

## 使用

#### 1.新建

`gitbook init`

#### 2.生成电子书

`gitbook serve`

#### 3.预览

用浏览器打开[http://localhost:4000](http://localhost:4000)
