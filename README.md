# -memo-
编程备忘




import concurrent.futures

with concurrent.futures.ProcessPoolExecutor(8) as executor:

(py的八核运算)



输出程序运算的时间

import time

start = time.clock()

...

end = time.clock()

print("Running time: %s Seconds"%(end - strat))





#coding:utf-8




http协议

get   下载的到网页内容 

post  提交表单给网站后台

# Anaconda 切换进入新环境
activate 

# 123
https://zhuanlan.zhihu.com/p/36036331?group_id=971929985087434752

# Spyder
使用Ctrl+SHIFT+Z能够反撤回

# Anaconda更新报错提示信息
C:\WINDOWS\system32>block should really be the equivalent of'block' 不是内部或外部命令，也不是可运行的程序或批处理文件。

将blcok前面的路径加入path（环境变量系统变量），如C:\WINDOWS\system32>

# Web
网页优化方面有一项措施是减少HTTP请求次数，就是把尽量多的css和js资源合并在一起，目的是尽量减少网页请求静态资源的次数，提高网页加载速度，同时减缓服务器的压力。

#搜索引擎代码 
例：site:steamcn.com 羞辱1汉化 
