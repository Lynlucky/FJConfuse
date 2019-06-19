# FJConfuse iOS混淆脚本
iOS混淆-拒绝4.3

`重要`：记得`备份X1` 记得`备份X2` 记得`备份X3`<br>

介绍<br>
=================
 * 用来混淆iOS<br>
 * 目前只支持oc

功能<br>
=================
 * 增加.h.m添加垃圾代码方法 自定义数量 方法长度等<br>
 * 修改类名前缀 包括.h .m .xib .storyborad<br>
 * 新增垃圾代码文件<br>

使用方法<br>
=================
 * TheProjectPath = ''  #项目路径 直接脱进来<br>
 * ThePrefix_New = 'NEW'   #类名新前缀<br>
 * ThePrefix_Old = 'OLD'   #类名旧前缀<br>
 * TheJunkCode_type = '' #暂无↔️<br>
 * TheJunkCode_count = 5  #生成垃圾代码方法数量<br>
 * TheJunkCode_methodslength =  16 #生成垃圾代码方法长度<br>
 * TheJunkCode_outlength =  10    #生成垃圾代码方法输出长度<br>
 * TheJunkCode_Dir  = ['Assets.xcassets','Base.lproj','MJRefresh','xcodeproj','XYTableViewNoDataView']  #过滤输入目录名即可 过滤注入垃圾代码的目录<br>
 * TheJunkCode_Filesuffix = ['.DS_Store','main.m','json','Info.plist']  #过滤文件名 既可以过滤类名修改和垃圾代码注入<br>
 * TheJunkFilePath = ''  #垃圾文件目录<br>
 * PCH_Path = '' #PCH路径<br>
 * TheJunkFilePathCount = 5  #文件数量（.h.m为1个）<br>
 
根据需求 然后运行即可 Python2 环境
=================
```javascript
   python ggconfusion.py
```

