测试函数
=====
1.ASCII<br>
返回与指定的字符对应的十进制数<br>
![](img8/1.png)<br>
2. CHR 
给出整数,返回对应的字符; <br>
![](img8/2.png)<br>
3. CONCAT 
连接两个字符串;<br>
![](img8/3.png)<br>
4. INITCAP 
返回字符串并将字符串的第一个字母变为大写; <br>
![](img8/4.png)<br>
5.INSTR(C1,C2,I,J) 
在一个字符串中搜索指定的字符,返回发现指定的字符的位置; <br>
C1 被搜索的字符串 <br>
C2 希望搜索的字符串 <br>
I 搜索的开始位置,默认为1 <br>
J 出现的位置,默认为1 <br>
![](img8/5.png)<br>
6.LENGTH 
返回字符串的长度; 
![](img8/6.png)<br>
7.LOWER <br>
返回字符串,并将所有的字符小写<br>
![](img8/7.png)<br>
8.UPPER <br>
返回字符串,并将所有的字符大写<br>
![](img8/8.png)<br>
9.RPAD和LPAD(粘贴字符) <br>
RPAD 在列的右边粘贴字符 <br>
LPAD 在列的左边粘贴字符<br>
![](img8/9.png)<br>
10.LTRIM和RTRIM 
LTRIM 删除左边出现的字符串<br> 
RTRIM 删除右边出现的字符串<br>
![](img8/10.png)<br>
11.SUBSTR(string,start,count) <br>
取子字符串,从start开始,取count个 <br>
![](img8/11.png)<br>
12.REPLACE(string,s1,s2) <br>
string 希望被替换的字符或变量 <br>
s1 被替换的字符串 <br>
s2 要替换的字符串 <br>
![](img8/12.png)<br>
13.SOUNDEX <br>
返回一个与给定的字符串读音相同的字符串<br>
![](img8/13.png)<br>
14.4.TRIM(s from string) 
LEADING 剪掉前面的字符 <br>
TRAILING 剪掉后面的字符 <br>
如果不指定,默认为空格符 <br>
15.ABS <br>
返回指定值的绝对值 <br>
![](img8/15.png)<br>
16.ACOS <br>
给出反余弦的值<br>
![](img8/16.png)<br>
17.ASIN <br>
给出反正弦的值 <br>
![](img8/17.png)<br>
18.ATAN <br>
返回一个数字的反正切值 <br>
![](img8/18.png)<br>
19.CEIL <br>
返回大于或等于给出数字的最小整数<br>
![](img8/19.png)<br>
20.COS <br>
返回一个给定数字的余弦 <br>
![](img8/20.png)<br>
21.COSH <br>
返回一个数字反余弦值 <br>
![](img8/21.png)<br>
22.EXP <br>
返回一个数字e的n次方根<br>
![](img8/22.png)<br>
23.FLOOR <br>
对给定的数字取整数<br>
![](img8/23.png)<br>
24.LN <br>
返回一个数字的对数值<br>
![](img8/24.png)<br>
25.LOG(n1,n2) <br>
返回一个以n1为底n2的对数<br>
![](img8/25.png)<br>
26.MOD(n1,n2)  <br>
返回一个n1除以n2的余数<br>
![](img8/26.png)<br>
27.POWER <br>
返回n1的n2次方根 <br>
![](img8/27.png)<br>
28.ROUND和TRUNC  <br>
按照指定的精度进行舍入  <br>
![](img8/28.png)<br>
29.SIGN <br>
取数字n的符号,大于0返回1,小于0返回-1,等于0返回0<br>
![](img8/29.png)<br>
30.SIN <br>
返回一个数字的正弦值<br>
![](img8/30.png)<br>
31.SIGH <br>
返回双曲正弦的值<br>
![](img8/31.png)<br>
32.SQRT <br>
返回数字n的根<br>
![](img8/32.png)<br>
33.TAN <br>
返回数字的正切值 <br>
![](img8/33.png)<br>
34.TANH <br>
返回数字n的双曲正切值 <br>
![](img8/34.png)<br>
35.TRUNC <br>
按照指定的精度截取一个数<br>
![](img8/35.png)<br>
36.ADD_MONTHS <br>
增加或减去月份<br>
![](img8/36.png)<br>
37.LAST_DAY <br>
返回日期的最后一天
![](img8/37.png)<br>
38.MONTHS_BETWEEN(date2,date1) <br>
给出date2-date1的月份 <br>
![](img8/38.png)<br>
39.NEW_TIME(date,this,that) <br>
给出在this时区=other时区的日期和时间 <br>
![](img8/39.png)<br>
40.NEXT_DAY(date,day) <br>
给出日期date和星期x之后计算下一个星期的日期 <br>
![](img8/40.png)<br>
41.SYSDATE <br>
用来得到系统的当前日期<br>
![](img8/41.png)<br>
trunc(date,fmt)<br>
按照给出的要求将日期截断,如果fmt=mi表示保留分,截断秒 <br>
![](img8/14.png)<br>
42.CHARTOROWID <br>
将字符数据类型转换为ROWID类型 <br>
43.CONVERT(c,dset,sset) <br>
将源字符串 sset从一个语言字符集转换到另一个目的dset字符集 <br>
![](img8/43.png)<br>
44.HEXTORAW <br>
将一个十六进制构成的字符串转换为二进制 <br>
45.RAWTOHEXT <br>
将一个二进制构成的字符串转换为十六进制 <br>
46.ROWIDTOCHAR <br>
将ROWID数据类型转换为字符类型<br>
47.TO_CHAR(date,format) <br>
将oracle里面的一个日期转换成字符串.<br>
![](img8/47.png)<br>
48.TO_DATE(string,format) 
将字符串转化为ORACLE中的一个日期 
49.TO_MULTI_BYTE <br>
将字符串中的单字节字符转化为多字节字符 <br>
![](img8/49.png)<br>
50.TO_NUMBER <br>
将给出的字符转换为数字 <br>
![](img8/50.png)<br>
51.BFILENAME(dir,file) <br>
指定一个外部二进制文件 <br>

