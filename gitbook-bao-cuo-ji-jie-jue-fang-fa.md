# Gitbook报错及解决方法

## 1.if \(cb\) cb.apply\(this, arguments\)错误

![1](f:/mybook/1.png)

​ 1.打开报错文件[C:\Program Files\nodejs\node\_modules\npm\node\_modules\gentle-fs\polyfills.js](https://github.com/bei66/gitbook/tree/aea233d9397add868d880b05aa28361e97d0ac26/Program%20Files/nodejs/node_modules/npm/node_modules/gentle-fs/polyfills.js)

​ 2.将62-64行代码注释

`fs.statSync = statFixSync(fs.statSync) fs.fstatSync = statFixSync(fs.fstatSync) fs.lstatSync = statFixSync(fs.lstatSync)`

[参考于](https://yimouleng.com/2020/09/28/if-cb-cb-applythis-arguments-error/)



## 2.TypeError \[ERR\_INVALID\_ARG\_TYPE\]: The "data" argument must be of type string or an instance of Buffe

`D:\code\JavaDance>gitbook init` `info: create SUMMARY.md`

`TypeError [ERR_INVALID_ARG_TYPE]: The "data" argument must be of type string or an instance of Buffer, TypedArray, or DataView. Received an instance of Promise`

### 错误原因

​ gitbook与node版本不兼容（已知node-v14.17 与 gitbook3.2.3不兼容）

### 解决办法

