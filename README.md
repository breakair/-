# python出现 'ascii' codec can't encode characters in position 问题解决方案

问题出现环境：windows7 python27<br>
解决方案：写入以下三行代码 
``` python 
import sys
reload(sys)
sys.setdefaultencoding('utf-8')
```
