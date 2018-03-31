- 为了开发过程中，每次修改源代码文件后，都自动编译项目，请运行如下命令：
```
npm run watch
```

- 在手机上安装[调试器APK](https://statres.quickapp.cn/quickapp/quickapp/201803/file/201803221213415527241.apk)，
- 安装[平台预览版](https://statres.quickapp.cn/quickapp/quickapp/201803/file/20180322121456491785.apk)
安装成功后，打开调试器应用如下图所示：
 
![Alt text](./1522163941637.png)

- 终端新开一个窗口，在项目根目录运行
```
npm run server
```
![Alt text](./1522164038896.png)

- 使用快应用调试器的扫码安装，扫描二维码，安装快应用
![Alt text](./1522164106222.png)

然后由于前面另外一个窗口运行着`npm run watch`，所以开发过程中，修改文件后，就会自动编译，然后快应用平台预览上就会自动更新了。

