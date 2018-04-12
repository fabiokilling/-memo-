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
