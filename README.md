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
### 首次执行：
1. **先引继帐号**，**先引继帐号**，**先引继帐号**，用手机自带的备份应用，或同品牌手机换机备份到另一台手机
2. 备份AuthKey，要在引继后备份，路径是 手机内部存储/Android/data/jp.co.lifewonders.housamo/files/Data/AuthKey
3. 备份obb文件，路径是 手机内部存储/Android/obb/jp.co.lifewonders.housamo/main.1212.jp.co.lifewonders.housamo.obb
4. JsHook -> 应用 -> housamo -> 注入Hook服务 -> 卸载再安装 -> 还原obb文件 -> 先不要启动Hook，把 **帐号引继** 或者 **进入主界面关闭游戏，覆盖AuthKey** 完成后，进入主界面确认是之前的账号，再启动Hook
### 游戏更新后：~
1. 用QooApp之类的下载游戏最新安装包
2. QooApp的下载的安装包路径为 手机内部存储/Android/data/com.qooapp.qoohelper/files/Download/game/jp.co.lifewonders.housamo
3. JsHook -> 安装包注入Hook服务 -> 选择下载的安装包 -> 安装 -> 启动
  
## 预览
![image](https://i.imgur.com/33Dyzty.jpg)
