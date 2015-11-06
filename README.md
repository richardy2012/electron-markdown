使用`electron`构建的markdown编辑器
### 历史
## 0.2.0
* 支持文件拖拽打开
* 增加菜单，支持文件：新建、打开、保存、另存为
* 打开本地文件时窗口标题会变为文件路径
* 已打开的文件被其它程序修改内容后会自动同步（忽视当前所做的修改）
## 0.1.0
* 实时预览
* 支持GFM
* Github的页面样式

### 构建
请先复制一份`gulpfile.sample.js`并重命名为`gulpfile.js`，根据你想构建的平台的不同可删除不需要的平台的代码
```shell
gulp
```
执行完成后会在`release`目录下生成Windows和Mac的可执行文件以及对应的zip包
