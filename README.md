# 東京放課後サモナーズ Mod
* 修改战斗相关功能
* 如果没有显示“注入完成”，可以设置1000毫秒这样的延迟

## 基础功能
* 我方锁血、锁CP

## 可选功能
* 游戏速度修改，在主界面长按“收件箱”图标1秒切换，在1倍、3倍、5倍之间切换
* 战斗开场不动直接胜利，在主界面长按“队伍与强化”图标1秒开关
* 进了战斗想开直接胜利可以长按“属性相性表”按钮2秒，然后需要动一下人物

## 免root相关
### 黑盒方法：
#### 首次执行：
1. 安装JsHook
2. 安装黑盒，一般来说安装BlackBox64 https://github.com/FBlackBox/BlackBox/releases
3. 打开BlackBox64 -> 右上角三点 -> 软件设置 -> 开启进程守护（防止闪退） -> 启动Xposed框架 -> 模块管理 -> 勾选JsHook -> 关闭BlackBox64
4. 如果BlackBox64的软件设置的“GMS管理”能开启，则开启，然后可以跳过5、6步，直接从第7步开始
5. 下载以下3个APK（谷歌三件套），注意查看下载路径
* https://github.com/xkeyC/x_google_installer/releases/tag/api28
* https://github.com/xkeyC/x_google_installer/releases/tag/s212417037
* https://github.com/xkeyC/x_google_installer/releases/tag/st82601710
6. 打开BlackBox64 -> 点+ -> 手动选择 -> 按顺序选择安装完以上3个APK
7. 打开BlackBox64 -> 点+ -> housamo -> 进入游戏出现无字提示后关闭
8. 外部使用文件应用，如MT管理器，把 手机内部存储/Android/data/jp.co.lifewonders.housamo/files/Data/AuthKey 复制到 手机内部存储/Android/data/top.niunaijun.blackboxa64/files/blackbox/storage/emulated/0/Android/data/jp.co.lifewonders.housamo/files/Data/AuthKey
9. 上一步也可以直接把 手机内部存储/Android/data/jp.co.lifewonders.housamo 整个复制到 手机内部存储/Android/data/top.niunaijun.blackboxa64/files/blackbox/storage/emulated/0/Android/data/jp.co.lifewonders.housamo
10. 复制obb文件 手机内部存储/Android/obb/jp.co.lifewonders.housamo/main.1212.jp.co.lifewonders.housamo.obb 复制到 手机内部存储/Android/data/top.niunaijun.blackboxa64/files/blackbox/storage/emulated/0/Android/obb/jp.co.lifewonders.housamo/main.1212.jp.co.lifewonders.housamo.obb
11. 打开BlackBox64 -> 打开JsHook -> 框架管理 -> 安装FridaMod
12. 打开BlackBox64 -> 打开JsHook -> 仓库 -> 下载脚本
13. 打开BlackBox64 -> 打开JsHook -> 应用 -> housamo -> 启动Hook服务 -> 启动配置（脚本配置） -> 延时设置1000 -> 选择注入框架“FridaMod” -> 启动下载的脚本 -> 运行游戏
#### 游戏更新后：
* 应该在外部更新游戏就行了？
* 如果出现无字情况，请再复制obb文件

### 普通方法：
#### 首次执行：
1. **先引继帐号**，**先引继帐号**，**先引继帐号**，用手机自带的备份应用，或同品牌手机换机备份到另一台手机
2. 备份AuthKey，要在引继后备份，路径是 手机内部存储/Android/data/jp.co.lifewonders.housamo/files/Data/AuthKey
3. 备份obb文件，路径是 手机内部存储/Android/obb/jp.co.lifewonders.housamo/main.1212.jp.co.lifewonders.housamo.obb
4. JsHook -> 应用 -> housamo -> 注入Hook服务 -> 卸载再安装 -> 还原obb文件 -> 先不要启动Hook，把 **帐号引继** 或者 **进入主界面关闭游戏，覆盖AuthKey** 完成后，进入主界面确认是之前的账号，再启动Hook
#### 游戏更新后：
1. 用QooApp之类的下载游戏最新安装包
2. QooApp的下载的安装包路径为 手机内部存储/Android/data/com.qooapp.qoohelper/files/Download/game/jp.co.lifewonders.housamo
3. JsHook -> 安装包注入Hook服务 -> 选择下载的安装包 -> 安装 -> 启动
  
## 预览
![image](https://i.imgur.com/33Dyzty.jpg)
