## naive使用   
  
### Windows,Linux,macOS
1. 下载[Nekoray](https://github.com/MatsuriDayo/nekoray/releases),然后解压.
2. 下载[naiveproxy](https://github.com/klzgrad/naiveproxy/releases)(自行选择对应系统,windows选择win-x64,linux选择linux-x64,mac:intel选择mac-x64,Apple Silicon选择mac-arm64),然后解压naive文件到Nekoray目录内  
**注意:是下载naiveproxy,不是cronet.**
**如果Assets显示很少,点击下面的Show all assets**
3. 启动Nekoray
4. 上方首选项->基本设置,通用页面内根据自己需求设置(建议监听地址0.0.0.0,端口1080),核心页面切换核心选择sing-box,下方naive选择Nekoray目录下刚才解压的naive程序,确定保存
5. 上方首选项->分组,新建分组,名称自己填喜欢的,类型选择订阅,url填订阅链接,确定,更新订阅
6. 选择需要节点即可使用    
    
### Android
1. 下载[SagerNet(github)](https://github.com/SagerNet/SagerNet/releases/download/0.8.1-rc02/SN-0.8.1-rc02-arm64-v8a.apk)(未必最新版本)或者[SagerNet(Google Play)](https://play.google.com/store/apps/details?id=io.nekohasekai.sagernet),安装
2. 下载[SagetNet-NaïveProxy插件(github)](https://github.com/SagerNet/SagerNet/releases/download/naive-plugin-106.0.5249.91-1/naive-plugin-106.0.5249.91-1-arm64-v8a.apk)(未必最新版本)或者[SagetNet-NaïveProxy插件(Google Play)](https://play.google.com/store/apps/details?id=io.nekohasekai.sagernet.plugin.naive),安装
3. 打开SagerNet,左上三横杠->分组,同[上方Windows,linux,macOS教程](#windowslinuxmacos)的第5步
4. 左上三条杠->配置,选择需要的节点启动即可   
   
### iOS
**iOS暂不支持订阅,只能手动添加(?)**  
1. 下载Shadowrocket,自行AppStore下载.
2. 右上+,类型选择https或者http2(**http2比较好?**),下方配置参考网页内配置,没有提到的配置保持默认,最后完成即可  
**设置多个节点可以长按已配置节点,拷贝粘贴,然后修改地址即可**
