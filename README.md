这里是我整理的atom 运行python环境需要用到的包，解压后将其中每一个包依次放到用户目录下的.atom/packages目录下，然后win+r打开cmd然后cd： 把script的目录拉进去，然后执行apm install即可，安装成功会显示done，然后可以apm list查看下是否安装成功


- [ ] [官方文档](https://atom.io/docs)  
- [x] [Atom编辑器折腾记](http://blog.csdn.net/bomess/article/category/3202419)  
- [x] [MAC版](http://www.imooc.com/article/1370)
- [x] [atom从入门到精通](http://blog.csdn.net/u010494080/article/category/6039322)
## atom本身的快捷键

快捷键(Linux/Windows) | 功能
---|---
`Ctrl + Shift + N` | 再打开一个ato编辑器
`Ctrl + N` | 新建一个空白文件
`Ctrl + O` | 打开文件
`Ctrl + Shift + O` | 打开文件夹
`Ctrl + Alt + O` | 添加项目文件夹
`Ctrl + Shift + T` | 重新加载上次项目
`Ctrl + S` | 保存文件
`Ctrl + Shift +S` | 另存为
`Ctrl + W` | 关闭当前编辑文档
`Ctrl + Shift + W` | 关闭编辑器
`Ctrl + Z` | 撤销
`Ctrl + Y` | 重做
`Shift + Delete` |剪切
`Ctrl + Insert` | 复制
`Ctrl + Shift + C` | 复制文档路径
`Shift + Insert` |粘贴
`Ctrl + A` | 全选
`Ctrl + Shift +U` | 设置文件的编码
`Ctrl + G` | 跳转到,Row:Column
`Ctrl + Shift + L` | 语法选择
`Ctrl+ Alt +R` | 重新载入当前编辑的文档
`F11` | 开启/关闭 全屏
`Ctrl + Shift + “+”` | 增大字体
`Ctrl + Shift + “-“` | 减小字体
`Ctrl + Shift + P` | 全局搜索面板
`Ctrl + L` | 选定一行
`Shift + Home` | 选定光标至行首
`Shift + End` | 选定光标至行尾
`Ctrl + Home` | 跳转到文件开头处
`Ctrl + End` | 跳转到文件结尾处
`Ctrl + Shift + Home` |选定光标处至文档首行
`Ctrl + Shfit + End` |选定光标处至文档尾行
`Ctrl + F` | 从缓存器搜索
`Ctrl + Shift + F` |高级替换
`Ctrl + D` | 匹配选定下一个
`Alt + F3` | 匹配选定所有
`Ctrl + P` | 查询文件,选定打开
`Ctrl + Del` | 删除光标至词尾
`Ctrl + Shift + D` |重复当前行
`Ctrl + Shift + K` | 删除当前行
`Ctrl + /` | 启用注释
`Ctrl + Alt + I` | 打开Chrome调试器
`Ctrl + [` | 向右缩进
`Ctrl + ]`  | 向左缩进
`Ctrl + up` | 行向上移动
`Ctrl + Down` | 行向下移动
`Ctrl + Enter` | 光标之下增加一行
`Ctrl + Shift + Enter` | 光标之上增加一行
`shift+ctrl+win+p` | 遇到不记得的命令可以通过此命令搜索

### python-tools
**ctrl+alt+u**   查找变量名，支持同步修改
![全局修改](https://i.github-camo.com/74ab6e10d2ee7f653156773afa9d7becd47139b3/687474703a2f2f692e696d6775722e636f6d2f636f4f6c426e372e6769663f31)

**ctrl+alt+g** 快速转到变量定义出， 支持自动打开文件    
![转到定义处](https://i.github-camo.com/e6d42a5fe7b9fe0fdac6983217bd27ada6b8fc26/687474703a2f2f692e696d6775722e636f6d2f695848593748452e6769663f31)

**ctrl+alt+e** 说是可以快速选定当前选定的字符串，在win下测试失败   
![快速选定](https://i.github-camo.com/fe211822532f7c89576111641e856d44f2baaa00/687474703a2f2f692e696d6775722e636f6d2f7455656475544b2e6769663f31)


### autocomplete-python    
*变量名自动补全*  

**ctrl+alt+g** 快速转到变量定义出， 支持自动打开文件      
![自动补全](https://i.github-camo.com/9cb3e21999f92079ca5393b718784f81be458afa/68747470733a2f2f636c6f75642e67697468756275736572636f6e74656e742e636f6d2f6173736574732f3139333836342f31323238383432372f36316665323131342d626130662d313165352d393833322d3938383639313830643837662e676966)


### simplified-chinese-menu   
*中文汉化*    

![汉化](https://i.github-camo.com/13fc3a0beae3d4aeb5d6569d720704d780822842/68747470733a2f2f6769746875622e636f6d2f6368696e616b6964732f61746f6d2d6368696e6573652d6d656e752f7261772f6d61737465722f73637265656e73686f742f73637265656e73686f742e706e67)


### activate-power-mode    
*装逼特效*/  

**ctrl+alt+o** 开关特效    
![装逼特效](https://i.github-camo.com/b1d03b9b7a9d7dc9a32d1eab307b5378f8c59a7b/68747470733a2f2f636c6f75642e67697468756275736572636f6e74656e742e636f6d2f6173736574732f3638383431352f31313631353536352f31306631363435362d396336352d313165352d386166342d3236356630316663383361302e676966)


### script   
*在Atom中运行脚本*   

作用 |	Mac OS X | Linux/Windows
--- |:--- |:---
运行脚本 |	`cmd-i`	| `shift-ctrl-b`
运行指定行号 |	`shift-cmd-j`	| `shift-ctrl-j`
配置运行参数 |	`shift-cmd-i`	| `shift-ctrl-alt-o`
通过配置文件运行 |	`shift-cmd-k`	| `shift-ctrl-alt-b`
关闭运行窗口 |	`esc` or `ctrl-w` |	`esc`
杀死进程 |	`ctrl-c` |	`ctrl-q`

### linter-pep8
*pep8自动检查*   
**安装**  
pip install pep8  
apm install linter-pep8  
基本使用不需要配置任何东西  
高级使用可以 在 扩展包里找到此包  设置pep8路径和需要忽略的风格编码(以逗号分隔)，全部的忽略项可以在[这里](http://pep8.readthedocs.io/en/latest/intro.html#error-codes)找到  
![样张](http://g.hiphotos.baidu.com/image/w%3D310/sign=a29f05483bfa828bd1239be2cd1e41cd/dcc451da81cb39dba85ce61bd8160924aa1830da.jpg)
