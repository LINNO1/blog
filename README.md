# blog
#VIM的使用
##VIM的模式
vim分为两种模式，命令模式和编辑模式。其中命令模式又可以分为Last line mode和command mode.
vim+文件名进入编辑画面，默认为命令模式，按【i】切换到编辑模式，可以编辑文件的内容。
按【esc】进入命令模式，在命令模式下输入【：】进入last line mode。
##VIM的基本操作
###模式间的切换
####命令模式到插入模式
【i】:从当前光标处输入文件
【a】:从当前光标的下一个位置输入文件
【o】:输入新的一行
####到命令模式
【ESC】
####命令模式到last line mode
【：】
###操作
####命令模式下
**移动光标**
Ctrl+b : 往后一页            
Ctrl+u  : 往前一页                      
Ctrl+b : 往后半页                   
Ctrl+d :往前半页 
数字 0：文章开头
 G:文章结尾 
$: 所在行最后一个字符的开头
^：所在行行首
w:下一字的开头
e:下个字的字尾
b:上一字的开头
nl:该行第n个字的开头
**删除文字**
x:删除光标后一个字符
nx:删除光标后n个字符
X:删除光标前一个字符
nX:删除光标前n个字符
dd:删除光标所在的一行
ndd:删除从光标所在的下n行
**复制和粘贴**
yw:复制一个字
nyw:复制n个字
yy:复制行
nyy:复制n行
p:粘贴
**替换**
r:替换光标所在处字
R:替换光标所到之处的字
**撤销上次操作**
u:撤销一次指令
**更改**
cw:更改光标到到字尾
**跳到指定行**
ctrl+g :列出光标所在行号
nG:光标跳到n行行首
####Last line mode
**列出行号**：  set nu
**跳到某行**： ：15(直接数字即可)
**查找字符**： /关键字 按n直到找到
**保存**：w
**离开**： q   q!（不保存强制离开）

[vim简单使用教程](http://www.cnblogs.com/onlyfu/p/5046910.html)
[vim入门教程](http://blog.jobbole.com/86132/)
![某大神总结的图片]( http://blog.chinaunix.net/attachment/201210/13/26000296_13500962024j36.jpg)
