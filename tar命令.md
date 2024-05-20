tar -zxvf 用于解压 .tar.gz 后缀结尾的<br>
tar -xvf 用于解压 .tar后缀结尾的<br>
<br>
这些都是tar的参数。.tar.gz是一个压缩包，.tar只是打包而没有压缩<br>
z：通过gzip支持压缩或解压缩<br>
x：解压缩。c是压缩<br>
v：在压缩或解压缩过程中显示正在处理的文件名<br>
f：f后面必须跟上要处理的文件名。也就是说你不能写成这样 tar -zxfv xxxx.tar.gz<br>
z代表gzip的压缩包；x代表解压；v代表显示过程信息；f代表后面接的是文件<br>
