# homuraCryptoTools

因为被py的库函数坑了无数次,所以决定把自己常用的函数打个包,暂时就放了DES Wiener 和 MD5 以后有想到别的再加

from homura import *
##wiener attack
wiener(e,n)

##md5 
md5s("string")

##DES （魔改过的，因为标准库中的实际有效位只有48位）
s=des("imnotkey")

s.setMode(ECB)

str="string"

s.encrypt(str)




安装

```
git clone https://github.com/wjbsyc/homuraCtyptoTools.git
cd homuraCtyptoTools
python setup.py install


```
