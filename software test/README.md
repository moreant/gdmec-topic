















- [第二十四课时作业](javascript:void(0))

## 一.单选题*（共3题,30.0分）*

*1*

数据的接收方想使用RSA方式进行数据加密。一般情况下，数据接收方是把什么密钥发给数据发送方，然后数据发送方用此密钥进行数据加密，然后把数据发回给数据接收方？

- A、

  公钥

- B、

  私钥

正确答案： A 我的答案：A得分： 10.0分

*2*

如果我们调用支付宝的接口，接收支付宝返回并加密过的数据，我们是使用什么密钥进行解密的？

- A、

  支付宝公钥

- B、

  应用公钥

- C、

  应用私钥

- D、

  支付宝私钥

正确答案： C 我的答案：C得分： 10.0分

*3*

如果我们调用支付宝的接口，一般需要配置三把密钥，自己生成的公钥和私钥（应用公钥，应用私钥），从支付宝获取到的支付宝公钥。如果我们需传数据给支付宝，应该使用那把密钥对数据进行加密？

- A、

  应用公钥

- B、

  应用私钥

- C、

  支付宝公钥

正确答案： C 我的答案：C得分： 10.0分

## 二.多选题*（共1题,10.0分）*

*1*

下面属于不可逆的加密算法有

- A、

  md5

- B、

  des

- C、

  rsa

- D、

  crypt

- E、

  sha1

正确答案： ADE 我的答案：ADE得分： 10.0分

## 三.判断题*（共6题,60.0分）*

*1*

crypt("加密字符串","盐值"):第二个参数盐值可选，如不填盐值，会使用随机值代替，那么每次生成的密文都一样

我的答案：*×* 得分： 10.0分正确答案：*×*

*2*

Rsa每次加密得到的密文是不一样的

我的答案：*√* 得分： 10.0分正确答案：*√*

*3*

crypt是单向的不可逆的加密算法



我的答案：*√* 得分： 10.0分正确答案：*√*

*4*

下载'实验24.doc'文档,自行相应的实验，此题选正确

我的答案：*√* 得分： 10.0分正确答案：*√*

*5*

RSA加密和解密的密钥是不一样的。DES加密和解密的密钥是一样的

我的答案：*√* 得分： 10.0分正确答案：*√*

*6*

由于RSA是非对称加密，因此加密和解密的密钥是不一样的

我的答案：*√* 得分： 10.0分正确答案：*√*









- [第二十三课时作业](javascript:void(0))

## 一.多选题*（共1题,12.5分）*

*1*

下面说法正确的是

- *A、*[DES是双向的可逆的加密解密算法](javascript:void(0))

- B、

  MD5是不可逆的算法

- C、

  SHA1是可逆的算法

- D、

  RSA是对称的双向可逆的加密解密算法

正确答案： AB 我的答案：AB得分： 12.5分

## 二.填空题*（共4题,50.0分）*

*1*

使用MD5加密得到的密文的长度都是固定(加密后为_________________位（bit），按照16进制（4位一个16进制数）编码后，就成了____________个字符

[正确答案：](javascript:void(0))

*第一空：* 128*第二空：* 32

我的答案：得分： 12.5分

*第一空：* 

128



*第二空：* 

32



批语

*2*

md5('abc')的值是_______________________________

[正确答案：](javascript:void(0))

*第一空：* 900150983cd24fb0d6963f7d28e17f72; 900150983cd24fb0d6963f7d28e17f72;  900150983cd24fb0d6963f7d28e17f72 ;900150983cd24fb0d6963f7d28e17f72

我的答案：得分： 12.5分

*第一空：* 

900150983cd24fb0d6963f7d28e17f72



批语

*3*

使用本次课目录下的CryptDes.php类，加密字符串abc,加密后的密文是________________

[正确答案：](javascript:void(0))

*第一空：* lFjeaEyHabE=; lFjeaEyHabE=; lFjeaEyHabE= ;lFjeaEyHabE=；IFjeaEyHabE=

我的答案：得分： 12.5分

*第一空：* 

lFjeaEyHabE=



批语

*4*

使用函数sha1，加密字符串abc，结果是___________________

[正确答案：](javascript:void(0))

*第一空：* a9993e364706816aba3e25717850c26c9cd0d89d

我的答案：得分： 12.5分

*第一空：* 

a9993e364706816aba3e25717850c26c9cd0d89d



批语

## 三.判断题*（共3题,37.5分）*

*1*

MD5摘要比SHA摘要长，因此，MD5的安全性更好一点，但加密速度会慢一点

我的答案：*×* 得分： 12.5分正确答案：*×*

*2*

下载"实验23.doc"并自行完成。本题选正确。

我的答案：*√* 得分： 12.5分正确答案：*√*

*3*

DES是单向的不逆的算法

我的答案：*×* 得分： 12.5分正确答案：*×*







- [第二十二课时作业](javascript:void(0))

## 一.单选题*（共3题,49.8分）*

*1*

xampp安装目录是c:\xampp，那么，httpd.conf配置文件所在的默认目录是？

- A、

  c:\xampp\

- B、

  c:\xampp\apache\bin

- C、

  c:\xampp\apache\conf\

  

- D、

  c:\xampp\htdocs

正确答案： C 我的答案：C得分： 16.6分

*2*

$test = "<script>'ok'";

$r = htmlentities($test);

$r的值最终为？



- A、

  <script>'ok'

- B、

  &lt;script&gt;'ok'

- C、

  &lt;script&gt;&#039;ok&#039

正确答案： B 我的答案：C得分： 0.0分

*3*

$test = "<script>'ok'";

$r = htmlentities($test, ENT_QUOTES);

$r的值最终为？



- A、

  <script>'ok'

- B、

  &lt;script&gt;'ok'

- C、

  &lt;script&gt;&#039;ok&#039

正确答案： C 我的答案：C得分： 16.6分

## 二.多选题*（共1题,16.6分）*

*1*

在appache里面配置https，并要强制http跳转到https一般需要修改那几个配置文件

- A、

  httpd.conf

- B、

  httpd-info.conf

- C、

  httpd-ssl.conf

- D、

  httpd-vhosts.conf

正确答案： ACD 我的答案：ACD得分： 16.6分

## 三.填空题*（共2题,33.6分）*

*1*

 $test = "<script>'ok'";

$r = strip_tags($test);

$r的值是________________



[正确答案：](javascript:void(0))

*第一空：* 'ok'

我的答案：得分： 16.6分

*第一空：* 

'ok'



批语

*2*

直接运行wamp，在配置过程中，如果配置出错，通常在apache的错误日志也无法查看错误的原因和出错的地方。所以，非常有必要使用命令行的启动apache服务，如出错，能看到相应的错误信息

方法是打开命令行提示窗口，然后转到apache的bin所在目录，运行_________________命令



[正确答案：](javascript:void(0))

*第一空：* httpd -t

我的答案：得分： 17.0分

*第一空：* 

httpd -t



批语





- [第二十一课时作业](javascript:void(0))



## 一.单选题*（共4题,50.0分）*

*1*

使用fiddler更改post数据，通过设置自动断点规则来实现。

![img](https://p.ananas.chaoxing.com/star3/origin/727012a24143f0fc4fa950b02b9c740b.png)

应该选择哪一项？

- A、

  Before Requests

- B、

  After Responses

- C、

  Disabled

- D、

  Ignore Images

正确答案： A 我的答案：A得分： 12.5分

*2*

使用fiddler更改post数据，用户再提交数据前，fiddler通过断点规则，实现了暂停，这时候，我们修改post的数据，本课程中，是通过选择哪个选项卡修改post数据的？

![img](https://p.ananas.chaoxing.com/star3/origin/ca8a2976e289531f2cc91a4b56a365dc.png)

- A、

  Headers

- B、

  TextView

- C、

  Raw

- D、

  XML

正确答案： B 我的答案：B得分： 12.5分

*3*

对字符串 admin 进行16进制转码，结果是？

- A、

  0x31323334

- B、

  0x70617373

- C、

  0x7573657273

- D、

  0x61646d696e

正确答案： D 我的答案：D得分： 12.5分

*4*

0X68656c6c6f十六进制转换为字符串是？

- A、

  hello

- B、

  admin

- C、

  users

- D、

  password

正确答案： A 我的答案：A得分： 12.5分

## 二.多选题*（共2题,25.0分）*

*1*

使用jmeter发送post数据包，post数据的表单名为xh,cj和submit，分别表示学号，成绩，和提交表单按钮，值为01，90，sub

在Body Data选项卡里面，应该输入 

- A、

  xh=01,cj=90,submit=submit

- B、

  xh=01&cj=90&submit=submit

- C、

  01&90&ubmit

- D、

  01,90,submit

正确答案： B 我的答案：B得分： 12.5分

*2*

使用jmeter发送post数据包，post数据的表单名为xh,cj和submit，分别表示学号，成绩，和提交表单按钮，可以选择哪个选项卡输入？

![img](https://p.ananas.chaoxing.com/star3/origin/62b890efe47215fa0d2ac3ab470f1dbf.png)

- A、

  Parameters

- B、

  Body Data

- C、

  Files Upload

正确答案： AB 我的答案：AB得分： 12.5分

## 三.判断题*（共2题,25.0分）*

*1*

使用jmeter发送post数据包，如果要发送到的网址需要验证登录状态。我们已经通过浏览器获取到cookie的信息，那么，为了使jmeter能顺利的把post数据包发出，可以通添加 HTTP信息头管理器 管理器，并无需对其进行配置

我的答案：*√* 得分： 0.0分正确答案：*×*

*2*

下载“实验21.doc",并自行完成。此题选正确

我的答案：*√* 得分： 12.5分正确答案：*√*



- [第二十课时作业](javascript:void(0))



## 一.单选题*（共5题,55.5分）*

*1*

要查询当前数据库的名称，sql语句是？

- A、

  SELECT DATABASE

- B、

  database()

- C、

  SELECT DATABASE()

- D、

  select db()

正确答案： C 我的答案：C得分： 11.1分

*2*

tb_grade表共有三个字段，下面哪一个选项的sql语句能正确运行？

- A、

  SELECT * FROM tb_grade UNION SELECT 3

- B、

  SELECT * FROM tb_grade UNION SELECT 1,2,3,4

- C、

  SELECT * FROM tb_grade UNION SELECT 'a','b','c'

- D、

  SELECT * FROM tb_grade UNION SELECT a,b,c

正确答案： C 我的答案：C得分： 11.1分

*3*



成绩表的所有记录如下

![img](https://p.ananas.chaoxing.com/star3/origin/777e082cba96a3a4a1c25838d90737b1.png)

SELECT GROUP_CONCAT(xh),GROUP_CONCAT(cj) FROM tb_grade的结果是？

- A、

  ![img](https://p.ananas.chaoxing.com/star3/origin/a0e94e4843ac2600b07db34fa0bb8ed9.png)

- B、

  ![img](https://p.ananas.chaoxing.com/star3/origin/1ded758f991bc2c0f22d16bad906a152.png)

- C、

  ![img](https://p.ananas.chaoxing.com/star3/origin/43e74bf9bfb2d29d92f993bb1ab07d03.png)

正确答案： A 我的答案：A得分： 11.1分

*4*

成绩表的所有记录如下

![img](https://p.ananas.chaoxing.com/star3/origin/777e082cba96a3a4a1c25838d90737b1.png)

SELECT * FROM tb_grade WHERE km='语文' # and cj>=90的查询结果为

- A、

  ![img](https://p.ananas.chaoxing.com/star3/origin/777e082cba96a3a4a1c25838d90737b1.png)

- B、

  ![img](https://p.ananas.chaoxing.com/star3/origin/0247e51c2e6c1068c2183b9b354292d5.png)

- C、

  ![img](https://p.ananas.chaoxing.com/star3/origin/6d9be6e9eef4ba3c887965ddbc25bb72.png)

正确答案： B 我的答案：B得分： 11.1分

*5*

下面是手工注入的操作步骤，

1.获取数据库中的表

2.猜解SQL查询语句中的字段数

3.下载数据

4.获取当前数据库

5.判断是否存在注入，注入是字符型还是数字型

6.确定显示的字段顺序

7.获取表中的字段名

如果按先后次序排列，正确的是？



- A、

  1234567

- B、

  5264173

- C、

  5264713

- D、

  6542713

正确答案： B 我的答案：B得分： 11.1分

## 二.多选题*（共1题,11.1分）*

*1*

已知成绩表tb_grade有三个字段，xh,km,cj分别表示学号，科目，成绩。查询成绩表所有内容，并且按成绩从大到小排序。下面，sql语句正确的是？

- A、

  SELECT * FROM tb_grade ORDER BY cj DESC

- B、

  SELECT * FROM tb_grade ORDER BY cj ASC

- C、

  SELECT * FROM tb_grade ORDER BY 3 DESC

- D、

  SELECT * FROM tb_grade ORDER BY 2 DESC

正确答案： AC 我的答案：AC得分： 11.1分

## 三.填空题*（共2题,22.2分）*

*1*

要查询数据库demo17里的tb_grade表的所有字段的名称，相应的查询语句是

SELECT  ___________  FROM information_schema.columns WHERE table_name='tb_grade' AND

___________ ='demo17'

[正确答案：](javascript:void(0))

*第一空：* column_name;GROUP_CONCAT(COLUMN_NAME)*第二空：* table_schema

我的答案：得分： 11.1分

*第一空：* 

column_name



*第二空：* 

table_schema



批语

*2*

要查询数据库dvwa所有表的名称，相应的查询语句

SELECT ___________ FROM information_schema.tables WHERE ____________='dvwa'



[正确答案：](javascript:void(0))

*第一空：* table_name;GROUP_CONCAT(table_name)*第二空：* table_schema

我的答案：得分： 11.1分

*第一空：* 

table_name



*第二空：* 

table_schema



批语

## 四.判断题*（共1题,11.2分）*

*1*

下载“实验20.doc"并完成。完成后，此题选正确即可

我的答案：*√* 得分： 11.2分正确答案：*√*





- [第十九课时作业](javascript:void(0))



## 一.单选题*（共6题,75.0分）*

*1*

使用sqlmap显示表tb_stuinf表的内容。要求只显示xh,xm两个字段的内容，下面命令正确的是？

- A、

  sqlmap.py -u"http://127.0.0.1/demo17/showgrade.php?xh=07120101" --cookie="PHPSESSID=3aie0lhgjmdeocj3j2p7t799j3" -D demo17 -T tb_stuinf -C xh,xm,class_name --dump

  

- B、

  sqlmap.py -u"http://127.0.0.1/demo17/showgrade.php?xh=07120101" --cookie="PHPSESSID=3aie0lhgjmdeocj3j2p7t799j3" -D demo17 -T tb_stuinf --dump

- C、

  sqlmap.py -u"http://127.0.0.1/demo17/showgrade.php?xh=07120101" --cookie="PHPSESSID=3aie0lhgjmdeocj3j2p7t799j3" -D demo17 -T tb_stuinf -C xh,xm --dump

- D、

  sqlmap.py -u"http://127.0.0.1/demo17/showgrade.php?xh=07120101" --cookie="PHPSESSID=3aie0lhgjmdeocj3j2p7t799j3" -D demo17 -T tb_stuinf xh,xm --dump

正确答案： C 我的答案：C得分： 12.5分

*2*

使用sqlmap进行post方式的自动搜索表单进行注入的操作，下面命令正确的是

- A、

  sqlmap.py -u"http://127.0.0.1/demo17/login.php" --forms

  

- B、

  sqlmap.py -u"http://127.0.0.1/demo17/login.php" --froms

- C、

  sqlmap.py -u"http://127.0.0.1/demo17/login.php" --auto

- D、

  sqlmap.py -u"http://127.0.0.1/demo17/login.php" 

正确答案： A 我的答案：A得分： 12.5分

*3*

使用sqlmap查询表tb_stuinf有什么字段，下面命令正确的是？

- A、

  sqlmap.py -u"http://127.0.0.1/demo17/showgrade.php?xh=07120101" --cookie="PHPSESSID=3aie0lhgjmdeocj3j2p7t799j3" -D demo17 -T tb_stuinf --col

  

- B、

  sqlmap.py -u"http://127.0.0.1/demo17/showgrade.php?xh=07120101" --cookie="PHPSESSID=3aie0lhgjmdeocj3j2p7t799j3" -D demo17 -T tb_stuinf --columns

- C、

  sqlmap.py -u"http://127.0.0.1/demo17/showgrade.php?xh=07120101" --cookie="PHPSESSID=3aie0lhgjmdeocj3j2p7t799j3" -D demo17 tb_stuinf --columns

- D、

  sqlmap.py -u"http://127.0.0.1/demo17/showgrade.php?xh=07120101" --cookie="PHPSESSID=3aie0lhgjmdeocj3j2p7t799j3" -D demo17  --columns

正确答案： B 我的答案：B得分： 12.5分

*4*

使用sqlmap显示数据库demo17中所有表的名称，下面命令正确的是？

- A、

  sqlmap.py -u"http://127.0.0.1/demo17/showgrade.php?xh=07120101" --cookie="PHPSESSID=3aie0lhgjmdeocj3j2p7t799j3" demo17 --tables

  

- B、

  sqlmap.py -u"http://127.0.0.1/demo17/showgrade.php?xh=07120101" --cookie="PHPSESSID=3aie0lhgjmdeocj3j2p7t799j3" -D demo17 -tables

  

- C、

  sqlmap.py -u"http://127.0.0.1/demo17/showgrade.php?xh=07120101" --cookie="PHPSESSID=3aie0lhgjmdeocj3j2p7t799j3" -T --tables

- D、

  sqlmap.py -u"http://127.0.0.1/demo17/showgrade.php?xh=07120101" --cookie="PHPSESSID=3aie0lhgjmdeocj3j2p7t799j3" -D demo17 --tables

正确答案： D 我的答案：D得分： 12.5分

*5*

使用sqlmap进行漏洞检测的时候，如果希望程序使用默认值自动应答，可以加

- A、

  --auto

- *B、*[--batch](javascript:void(0))

- C、

  --default

- D、

  --auto-default

正确答案： B 我的答案：B得分： 12.5分

*6*

使用fiddler来获取某次http连接的post请求头部信息，应该选择下面哪个选项卡

![img](https://p.ananas.chaoxing.com/star3/origin/70c0eff8178fbabc5845d9c28c5c4401.png)

- A、

  TextView

- B、

  SyntaxView

- C、

  WebForms

- D、

  Raw

正确答案： D 我的答案：D得分： 12.5分

## 二.多选题*（共1题,12.5分）*

*1*

sqlmap检测过的站都会生成一个文件夹存放记录文件，要清除检测的结果，可以

- A、

  删除记录文件所在的目录

- B、

  使用命令 --clear

- C、

  使用命令 --clear--output

- D、

  使用命令--purge

正确答案： AD 我的答案：AD得分： 12.5分

## 三.判断题*（共1题,12.5分）*

*1*

下载"实验19.doc"并完成，完成后，此题选正确。

我的答案：*√* 得分： 12.5分正确答案：*√*







- [第十七课时作业](javascript:void(0))



## 一.单选题*（共3题,30.0分）*

*1*

某成绩管理系统有一个根据学号查询成绩的功能，其查询语句如下

$Sql = 'select * from tb_grade where xh='.$_GET['xh'];

系统对表单的输入内容并无任何过滤处理。

如服务器的地址是localhost，显示成绩所在的页面是showgrade.php。如想显示所有学生的成绩，那么只需在浏览器输入

- A、

  http://localhost/showgrade.php

- B、

  http://localhost/showgrade.php?id=1

- C、

  http://localhost/showgrade.php?xh=1 or 1=1

- D、

  http://localhost/showgrade.php?xh=1' or '1'='1

正确答案： C 我的答案：C得分： 10.0分

*2*

LoadRunner可以通过一台机器，向多台安装有Loade Generators的机器分配压力测试任务，向测试对象发起压力测试。接收任务的机器要确保



- A、

  Analysis已经启动

- B、

  Virtual User Generator已经启动

- C、

  LoadRunner Agent Processer代理进程已经启动

- D、

  Controller已经启动

正确答案： C 我的答案：C得分： 10.0分

*3*

某成绩管理系统有一个根据学号查询此学生信息的功能，其查询语句如下

$sql = "select * from tb_stuinf where xh = '$xh'";

系统对表单的输入内容并无任何过滤处理。

如服务器的地址是localhost，显示成绩所在的页面是showstu.php。如想显示所有学生的成绩，那么只需在浏览器输入



- A、

  http://localhost/showstu.php

- B、

  http://localhost/showstu.php?id=1

- C、

  http://localhost/showstu.php?xh=1 or 1=1

- D、

  http://localhost/showstu.php?xh=1' or '1'='1

正确答案： D 我的答案：D得分： 10.0分

## 二.多选题*（共3题,30.0分）*

*1*



某成绩管理系统有一个根据学号查询成绩的功能，其查询语句如下

$Sql = 'select * from tb_grade where xh='.$_GET['xh'];

系统对表单的输入内容并无任何过滤处理。

如服务器的地址是localhost，显示成绩所在的页面是showgrade.php。如想显示所有学生的成绩，那么只需在浏览器输入



- A、

  http://localhost/showgrade.php?xh=1 or 1=1

- B、

  http://localhost/showgrade.php?xh=1 or '1'='1'

- C、

  

  http://localhost/showgrade.php?xh=1' or '1'='1

- D、

  http://localhost/showgrade.php?xh=1 or 'a'='a'

正确答案： ABD 我的答案：ABD得分： 10.0分

*2*

某成绩管理系统登录功能中，判断用户名和密码是否正确是通过以下sql语句

select * from tb_stuinf where xh = '$name' and pwd = '$password'

的查询结果。系统对表单的输入内容并无任何过滤处理。登录的界面如下

![img](https://p.ananas.chaoxing.com/star3/origin/dbe3f64122f1116ac4452c7d431f28d0.png)

假设已经知道用户名07120101是有效的，密码不知道。那么，在用户名和密码框输入什么内容，能成功登录进入到系统

- A、

  用户名输入：07120101'#

  密码输入：abc

- B、

  用户名输入：07120101'#

  密码框随便输入一些内容或者不输入任何内容

  

- C、

  用户名输入：07120101

  密码输入：a' or '1'='1

- D、

  用户名输入：07120101

  密码输入：1 or 1=1

  

正确答案： ABC 我的答案：ABC得分： 10.0分

*3*

某成绩管理系统有一个根据学号查询成绩的功能，通过以下语句来获取成绩

$xh = $_GET['xh'];	

$xh = addslashes($xh);

$sql = "select * from tb_grade where xh = $xh";	

如服务器的地址是localhost，显示成绩所在的页面是showgrade.php。如想显示所有学生的成绩，那么只需在浏览器输入



- A、

  http://localhost/showgrade.php?xh=1 or 1=1

- B、

  http://localhost/showgrade.php?xh=1 or '1'='1'

- C、

  http://localhost/showgrade.php?xh=1' or '1'='1

- D、

  http://localhost/showgrade.php?xh=1 or 2=2

正确答案： AD 我的答案：AD得分： 10.0分

## 三.判断题*（共4题,40.0分）*

*1*

下载“实验17.doc"并完成，完成后，此题选正确即可

我的答案：*√* 得分： 10.0分正确答案：*√*

答案解析：

第二大题第1小题

![img](https://mooc1-1.chaoxing.com/js/editor20150812/dialogs/attachment_new/fileTypeImages/icon_default.gif)[showgrade.php](https://mooc1-1.chaoxing.com/ueditorupload/read?objectId=56db7c7858ff0a6be34da06a641fef4a&fileOriName=showgrade.php)

第二大题第2小题

![img](https://mooc1-1.chaoxing.com/js/editor20150812/dialogs/attachment_new/fileTypeImages/icon_default.gif)[showstu.php](https://mooc1-1.chaoxing.com/ueditorupload/read?objectId=636eb7ce01d51140fec1910b14d6f9f7&fileOriName=showstu.php)

第二大题第3小题

![img](https://mooc1-1.chaoxing.com/js/editor20150812/dialogs/attachment_new/fileTypeImages/icon_default.gif)[logindo.php](https://mooc1-1.chaoxing.com/ueditorupload/read?objectId=b15d1e907a53255f6b80c17751bc7775&fileOriName=logindo.php)



*2*

某成绩管理系统登录功能中，判断用户名和密码是否正确是通过以下语句

$name = $_POST['name'];		

$password = $_POST['password'];		

$name = addslashes($name);

$password = addslashes($password);

select * from tb_stuinf where xh = '$name' and pwd = '$password'

登录的界面如下

![img](https://p.ananas.chaoxing.com/star3/origin/dbe3f64122f1116ac4452c7d431f28d0.png)

假设已经知道用户名07120101是有效的，密码不知道。那么，在用户名输入：07120101，密码输入：1' or '1'='1 就能成功登录。

我的答案：*×* 得分： 10.0分正确答案：*×*

*3*



某成绩管理系统有一个根据学号查询成绩的功能，通过以下语句来获取成绩

$xh = $_GET['xh'];				

$pat = '/\d{8}/';

if(!preg_match($pat,$xh)) return;

$sql = "select * from tb_grade where xh = $xh";	

如服务器的地址是localhost，显示成绩所在的页面是showgrade.php。如想显示所有学生的成绩，那么只需在浏览器输入http://localhost/showgrade.php?xh=1 or 1=1



我的答案：*×* 得分： 10.0分正确答案：*×*

*4*

某成绩管理系统登录功能中，判断用户名和密码是否正确是通过以下语句

$name = $_POST['name'];

$password = $_POST['password'];

$name = addslashes($name);

$password = addslashes($password);

select * from tb_stuinf where xh = '$name' and pwd = '$password'

登录的界面如下

![img](https://p.ananas.chaoxing.com/star3/origin/dbe3f64122f1116ac4452c7d431f28d0.png)

假设已经知道用户名07120101是有效的，密码不知道。那么，在用户名输入：07120101'#，密码不输入任何内容，就能成功登录



我的答案：*×* 得分： 10.0分正确答案：*×*





- [第十六课时作业](javascript:void(0))



## 一.单选题*（共9题,90.0分）*

*1*

在下面的LR中关联函数中，哪个是使用正则表达式来关联的？

- A、

  web_reg_save_param_regexp

- B、

  web_reg_save_param

- C、

  web_reg_save_param_ex

- D、

  web_reg_save_param_json_JS

正确答案： A 我的答案：A得分： 10.0分

*2*

使用LR录制了一段脚本，功能是使用用户名jojo，密码bean登录webtours。但回放的时候，发现并没有登录成功，在快照看到如下图的错误

![img](https://p.ananas.chaoxing.com/star3/origin/31d54bbe934478501e5ee5fc8b95e8af.png)

原因是

- A、

  脚本没有动态捕获系统动态生成并保存在session的验证字符串，并在登录的时候提交此字符串的值

- B、

  用户名错误

- C、

  密码错误

正确答案： A 我的答案：A得分： 10.0分

*3*

使用LR进行性能测试，需要配置模拟10个用户向测试服务器发送请求，具体是使用LR里面的哪个工具？

- A、

  Virtual User Generator

- B、

  Controller

- C、

  Analysis

正确答案： B 我的答案：B得分： 10.0分

*4*

检查点函数的作用是

- A、

  检查是否能成功连接服务器

- B、

  检查服务器是否返回了数据

- C、

  检查用户名和密码是否正确

- D、

  判定是否返回了和期望一致的值，如返回值和期望值一致，表示测试通过

正确答案： D 我的答案：D得分： 10.0分

*5*

在LR中，使用关联函数获取动态值，这个值的左边的字符串是"hello"，右边的字符串是ok,那么应该如何填写相应的参数

- A、

  ![img](https://p.ananas.chaoxing.com/star3/origin/9b41585924ee560b7539ef9f8f1a331c.png)

- B、

  web_reg_save_param("myvalue",

   "LB=\"hello\"",

   "RB=ok",

   LAST);

- C、

  web_reg_save_param("myvalue",

   "LB=hello",

   "RB=ok",

   LAST);

  

- D、

  web_reg_save_param("myvalue",

   "LB="hello"",

   "RB=ok",

   LAST);

  

正确答案： B 我的答案：B得分： 10.0分

*6*

使用LR进行性能测试，需要在Controller把当前的测试结果发到Analysis工具，进行测试结果数据分析，首先要选择菜单的哪一项？

![img](https://p.ananas.chaoxing.com/star3/origin/fdd12f31fcac53d5f5a48f3a0baac13b.png)

- A、

  Tools

  

- B、

  Results

  

- C、

  Scenario 

- D、

  Diagnostics

正确答案： B 我的答案：B得分： 10.0分

*7*

使用LR进行性能测试，如需修改脚本，具体是使用LR里面的哪个工具？

- A、

  Analysis

- B、

  Controller

- C、

  Virtual User Generator

正确答案： C 我的答案：C得分： 10.0分

*8*

在LR中，要获取关联值，需要把关联函数放在提交http请求的函数的

- A、

  前面

- B、

  后面

- C、

  前后都无所谓

正确答案： A 我的答案：A得分： 10.0分

*9*

下面哪个是检查点函数

- A、

  web_submint_data

- B、

  web_reg_find

- C、

  lr_start_transaction

- D、

  web_reg_save_param

正确答案： B 我的答案：B得分： 10.0分

## 二.多选题*（共1题,10.0分）*

*1*

关于LR中的事务，下面说法的正确的是

- A、

  事务函数必须成对出现

- B、

  事务开始函数的和事务结束函数的第一个参数是用来表示事务的名称。

- C、

  lr_end_transcaction是事务结束函数

- D、

  lr_start是事务开始函数

正确答案： ABC 我的答案：ABC









- [第十五课时作业](javascript:void(0))

## 一.单选题*（共10题,100.0分）*

*1*

hp的测试网站WebTours的用户信息，订单等数据是存放在？

- A、

  sqlite数据库

- B、

  access数据库

- C、

  mysql数据库

- *D、*[webTours安装目录下的cgi-bin\users目录下的可以用记事本打开的文本格式的文件](javascript:void(0))

正确答案： D 我的答案：D得分： 10.0分

*2*

webtours安装完成后，默认的端口是

- A、

  80

- B、

  8080

- C、

  1080

- D、

  443

正确答案： C 我的答案：C得分： 10.0分

*3*

在LR中，需设置脚本的迭代次数，应该

- A、

  打开Replay-->Runtime Settings..进行设置

- B、

  打开Record-->Runtime Settings..进行设置

- C、

  打开Record-->Record Options..进行设置

- D、

  打开Desig->Parameters..进行设置

正确答案： A 我的答案：A得分： 10.0分

*4*

在LR中，如希望每次迭代都重新取值，下面的参数应该选

![img](https://p.ananas.chaoxing.com/star3/origin/9ff52cce07a92560369b4c1951bccacd.png)

- A、

  Once

- B、

  Each iteration

- C、

  Eache occurence

正确答案： B 我的答案：B得分： 10.0分

*5*

在LR里面，用来编写脚本的工具是？

- A、

  Virtual User Generator

- B、

  Controller

- C、

  Analysis

- D、

  Agent Process

正确答案： A 我的答案：A得分： 10.0分

*6*

在LR中，需参数化值，选择此值，右击鼠标，出现如下弹出菜单

![img](https://p.ananas.chaoxing.com/star3/origin/9ca9ef694a589d6b20e1a85a6b4015f8.png)
接下来应该选项哪一项？

- A、

  Insert

- B、

  Correlate Selection

- C、

  Replace with Parameter

正确答案： C 我的答案：C得分： 10.0分

*7*

如希望观看回放的快照snap shots，出现以下提示，

![img](https://p.ananas.chaoxing.com/star3/origin/ed1da3124361d141cf6312ea6635689f.png)需要打开 Tools->Options->Scripting->SnanpShots并进行设置，才能看到快照，具体如何设置？

- A、

  ![img](https://p.ananas.chaoxing.com/star3/origin/a7334fa24f05600dae71dd62ff015071.png)

- B、

  ![img](https://p.ananas.chaoxing.com/star3/origin/ec55c701c7bf19c10d63bfd89a6d13ce.png)

- C、

  ![img](https://p.ananas.chaoxing.com/star3/origin/063adac1285c3985f18cb56b6cbda4da.png)

正确答案： C 我的答案：C得分： 10.0分

*8*

在LR中，如希望取值的方式是按顺序取，下面应该选择

![img](https://p.ananas.chaoxing.com/star3/origin/5cabb984ea02d8f167f9db6004f1cd98.png)

- A、

  Random

- B、

  Sequential

- C、

  Unique

正确答案： B 我的答案：B得分： 10.0分

*9*

使用postman来测试本次课使用laravel编写的Restful标准的接口，接口的动作为post。那么，填写请求的body时，需选择

- A、

  none

- B、

  form-data

- C、

  x-www-form-urlencode

- D、

  raw

正确答案： D 我的答案：D得分： 10.0分

*10*

使用jmeter来测试本次课使用laravel编写的Restful标准的接口，接口的动作为post。那么，http请求采用器填写post的数据，最好选择

- A、

  ![img](https://p.ananas.chaoxing.com/star3/origin/30eb4fc5d2fd0b081be51dd1d240e010.png)

- B、

  ![img](https://p.ananas.chaoxing.com/star3/origin/c773741f72749895ba1081b3757d35da.png)

- C、

  ![img](https://p.ananas.chaoxing.com/star3/origin/14877423ba13ef14feb0feb472e5a475.png)

正确答案： B 我的答案：B





- [第十四课时作业](javascript:void(0))

## 一.单选题*（共6题,60.0分）*

*1*

在php中使用curl通过http-post的方式来访问接口，获取数据，下面的说法正确是

（10.0分）

- A、

  使用默认配置即可

- B、

  需添加以下代码

   curl_setopt($curl, CURLOPT_POST, 1);

正确答案： B 我的答案：B得分： 10.0分

*2*

在谷歌或火狐浏览器输入[http://wthrcdn.etouch.cn/weather_mini?city=北京](http://wthrcdn.etouch.cn/weather_mini?city=北京，)

出现以下乱码

![img](https://p.ananas.chaoxing.com/star3/origin/c68ef6ce6b4b75c04dfe26c9df74c956.png)

的情况，可以把使用火狐浏览器把编码格式改为什么格式就能正常显示天气预报的内容？

![img](https://p.ananas.chaoxing.com/star3/origin/a932e7c003882953692f97de91c67bcc.png)

（10.0分）

- A、

  简体中文

  

- B、

  西文

- C、

  Unicode

- D、

  繁体中文

正确答案： C 我的答案：C得分： 10.0分

*3*

在php中使用curl通过http-get的方式来访问接口，获取数据，下面的说法正确是

（10.0分）

- A、

  使用默认配置即可

  

- B、

  需添加以下代码

   curl_setopt($curl, CURLOPT_POST, 1);

正确答案： A 我的答案：A得分： 10.0分

*4*

默认情况下IIS Express的配置文件所在的目录是？

（10.0分）

- A、

  C:\Program Files (x86)\IIS Express\Config

- B、

  C:\Program Files\IIS Express\Config

- C、

  我的文档目录下的

  文档\IIS Express\Config

正确答案： C 我的答案：C得分： 10.0分

*5*

默认情况下IIS Express的可执行程序安装目录是

（10.0分）

- A、

  C:\Program Files (x86)\IIS Express

- B、

  C:\Program Files \Microsoft\IIS Express

- C、

  我的文档目录下的

  文档\IIS Express\Config

  

- D、

  C:\IIS Express

正确答案： A 我的答案：A得分： 10.0分

*6*

在PHP中使用curl出现乱码和解决方法

用curl获取一个经过gzip压缩后的网页时返回乱码。如

http://wthrcdn.etouch.cn/weather_mini?city=北京

需要如何解决



（10.0分）

- A、

  添加代码

   curl_setopt($curl, CURLOPT_HEADER, 0);

- B、

  添加代码

  curl_setopt($curl,CURLOPT_ENCODING ,'gzip')

  

- C、

  添加代码

  curl_setopt($curl,CURLOPT_ENCODING ,'utf-8')

  

- D、

  添加代码

  curl_setopt($curl,CURLOPT_GZIP)

正确答案： B 我的答案：B得分： 10.0分

## 二.判断题*（共3题,40.0分）*

*1*

IISExpress的配置文件applicationhost.config在安装完成后就自动生成

（15.0分）

我的答案：*×* 得分： 15.0分正确答案：*×*

*2*

下载”实验14.doc“文档，并自行完成，完成后，此题选择正确。

（10.0分）

我的答案：*√* 得分： 10.0分正确答案：*√*

答案解析：

![img](https://mooc1-1.chaoxing.com/js/editor20150812/dialogs/attachment_new/fileTypeImages/icon_default.gif)[getctiy.php](https://mooc1-1.chaoxing.com/ueditorupload/read?objectId=276f5e25385722f90eda6470ed65faa9&fileOriName=getctiy.php)

![img](https://mooc1-1.chaoxing.com/js/editor20150812/dialogs/attachment_new/fileTypeImages/icon_default.gif)[translate.php](https://mooc1-1.chaoxing.com/ueditorupload/read?objectId=f7958caf400cacc39683bf7a7d6bcdc5&fileOriName=translate.php)

![img](https://mooc1-1.chaoxing.com/js/editor20150812/dialogs/attachment_new/fileTypeImages/icon_default.gif)[weather.php](https://mooc1-1.chaoxing.com/ueditorupload/read?objectId=1f546125cf2f1e04989b8eea9e5d9228&fileOriName=weather.php)



*3*

IISExpress的配置文件applicationhost.config是在第一次运行IISExpress后才会生成。

（15.0分）

我的答案：*√* 得分： 15.0分正确答案：*√*



- [第十三课时作业](javascript:void(0))



## 一.判断题*（共1题,100.0分）*

*1*

下载“实验13.doc”并完成。完成后，此题选正确。

我的答案：*√* 得分： 100.0分正确答案：*√*

答案解析：

![img](https://mooc1-1.chaoxing.com/js/editor20150812/dialogs/attachment_new/fileTypeImages/icon_default.gif)[showcity.php](https://mooc1-1.chaoxing.com/ueditorupload/read?objectId=16e4d6c959bc061251e87b01eacf93c8&fileOriName=showcity.php)

![img](https://mooc1-1.chaoxing.com/js/editor20150812/dialogs/attachment_new/fileTypeImages/icon_default.gif)[weatherinf.php](https://mooc1-1.chaoxing.com/ueditorupload/read?objectId=95c9515ebfd91a848776b9e9ea00125f&fileOriName=weatherinf.php)





- [第十二课时作业](javascript:void(0))



## 一.单选题*（共6题,75.0分）*

*1*

在jmeter中配置“FTP请求"采样器元件匿名访问ftp服务器。用户名如何配置？

（15.0分）

- A、

  不用填写

- B、

  填写anonymous

- C、

  填写user

- D、

  填写users

正确答案： B 我的答案：B得分： 15.0分

*2*

FileZillaServer设置目录的权限如下图

![img](https://p.ananas.chaoxing.com/star3/origin/2c7f263b5c93301bc713a10976d1ee21.png)

（10.0分）

- A、

  此目录下的文件可读可写

  此目录能获取目录列表。能创建和删除子目录。

- B、

  此目录下的文件可读可写

  此目录能获取目录列表。

  

- C、

  此目录下的文件只读

  此目录能获取目录列表。

  

- D、

  此目录下的文件只读

  此目录能获取目录列表。能删除子目录

  

正确答案： C 我的答案：C得分： 10.0分

*3*

在jmeter中配置“FTP请求"采样器元件上传文件，

![img](https://p.ananas.chaoxing.com/star3/origin/961c9b7aa8577456b9e80649445b2d02.png)

应该选

（15.0分）

- A、

  get(RETR)

- B、

  put(STOR)

正确答案： B 我的答案：B得分： 15.0分

*4*

ftp的匿名用户的用户名是

（10.0分）

- A、

  anonymous

- B、

  user

- C、

  admin

- D、

  users

正确答案： A 我的答案：A得分： 10.0分

*5*

![img](https://p.ananas.chaoxing.com/star3/origin/66b1428e310f1d2a6a64201b251943ab.png)

上图是FileZillaServer用户的目录设置，哪个是根目录？

（10.0分）

- A、

  E:\javacode

- B、

  D:\php

正确答案： B 我的答案：B得分： 10.0分

*6*

如希望把目录E:\javacode（下图所示）显示在根目录下，并且目录名为java

![img](https://p.ananas.chaoxing.com/star3/origin/66b1428e310f1d2a6a64201b251943ab.png)

那应该在别名设置的地方，把此目录的别名设置为

（15.0分）

- A、

  java

- B、

  /java

- C、

  D:/php/java

- D、

  H/java

正确答案： B 我的答案：D得分： 0.0分

## 二.多选题*（共1题,20.0分）*

*1*

使用windows资源管理器访问ftp服务器。

服务器地址是192.168.199.153

ftp用户名是:test

密码是：123456

下面操作正确的是

（20.0分）

- A、

  在地址栏输入

  ![img](https://p.ananas.chaoxing.com/star3/origin/fdf7c937195ef91d524708e0e60189df.png)

- B、

  

  [在地址栏输入](javascript:void(0))[ftp://192.168.199.153](http://ftp//192.168.199.153)

  然后右击，选择“登录”，输入用户名和密码

- C、

  

  [在地址栏输入](javascript:void(0))[ftp://192.168.199.153?user=test&password=123456](http://ftp//192.168.199.153)

  

正确答案： AB 我的答案：AB得分： 20.0分

## 三.判断题*（共1题,5.0分）*

*1*

下载“实验12.doc”。自行完成。结果不用上传，完成后，此题选正确。

（5.0分）

我的答案：*√* 得分： 5.0分正确答案：*√*



- [第十一课时作业](javascript:void(0))



## 一.判断题*（共1题,100.0分）*

*1*

下载"实验11.doc"和相关文件，完成实验，完成后结果不用上传，此题目选正确即可。作业提交后，可以查看答案解析。下载jmx参考代码

我的答案：*√* 得分： 100.0分正确答案：*√*

答案解析：

![img](https://mooc1-1.chaoxing.com/js/editor20150812/dialogs/attachment_new/fileTypeImages/icon_default.gif)[11测试sqlserver.jmx](https://mooc1-1.chaoxing.com/ueditorupload/read?objectId=d992049a9589235f822bb98e8fdc091a&fileOriName=11测试sqlserver.jmx)



- [第十课时作业](javascript:void(0))

## 一.判断题*（共1题,100.0分）*

*1*

下载"实验10.doc"和相关文件，完成实验，完成后结果不用上传，此题目选正确即可。作业提交后，可以查看答案解析。

我的答案：*√* 得分： 100.0分正确答案：*√*

答案解析：

此题目需要先执行删除成绩的操作。但是，默认情况下，线程组执行的顺序是并发的。所以，有可能成绩表还未删除完成，下面插入成绩的操作就已经开始执行了。并且，刚刚插入的成绩记录在数据库表里面是已经存在的，那么，就可能会出现有若干条记录插入失败，并提示主键冲突。如下图

![img](https://p.ananas.chaoxing.com/star3/origin/68e0999d94ded490bc344be40182abc1.png)

所以，最好是让线程组从上到下的顺序执行。

方法是选择测试计划，在右边的属性勾选上“独立运行每个线程组..."

![img](https://p.ananas.chaoxing.com/star3/origin/308048c8acc95894a5ea14ea0801ee6a.png)

![img](https://mooc1-1.chaoxing.com/js/editor20150812/dialogs/attachment_new/fileTypeImages/icon_default.gif)[10-数据库测试.jmx](https://mooc1-1.chaoxing.com/ueditorupload/read?objectId=d71f926df3c36f2f14f84dc2004e8f53&fileOriName=10-数据库测试.jmx)





- [第九课时作业](javascript:void(0))



## 一.单选题*（共7题,80.0分）*

*1*

正则表达式为：a.*?b

字符串为：abcdefgab

第一次匹配的结果为

（15.0分）

- A、

  abcdefgab

- B、

  ab

正确答案： B 我的答案：B得分： 15.0分

*2*

下面是经过url编码后的字符

%e4%bd%a0%e7%8c%9c%e4%b8%8d%e5%88%b0

那么，对其进行解码后，对应的内容应该是？

（10.0分）

- A、

  hello

- B、

  提交

- C、

  你好

- D、

  你猜不到

正确答案： D 我的答案：D得分： 10.0分

*3*

使用jmeter中的配置元件来读取本次课的grade(utf-8).csv文件里面的学号，科目和成绩。配置如下图

![img](https://p.ananas.chaoxing.com/star3/origin/7aeb31bd51bcfa710bce82dd894c62af.png)

如果在其他元件中要获取学号的值，代码应该怎么写



（10.0分）

- A、

  $p1

- B、

  p1

- C、

  ${p1}

- D、

  {p1}

正确答案： C 我的答案：C得分： 10.0分

*4*

使用jmeter测试本次课的例子web应用demo9。出现了如下图所示的结果。原因是

![img](https://p.ananas.chaoxing.com/star3/origin/c35aa9e2784521907aba38526ca818ec.png)

![img](https://p.ananas.chaoxing.com/star3/origin/dc87d3cc271aa44258409dde395c71b7.png)

（10.0分）

- A、

  用户名和密码错误

- B、

  没有添加http cookie 管理器元件

- C、

  登录超时了

正确答案： B 我的答案：B得分： 10.0分

*5*

下图的匹配数字（0代表随机）：中的值1表示意思
![img](https://p.ananas.chaoxing.com/star3/origin/b3ddd991ce28deddb806b6a10762fb8c.png)

（10.0分）

- A、

  随机取匹配到的值

- B、

  取第1次匹配到的值

- C、

  取表达式第1个括号的规则的值

正确答案： B 我的答案：B得分： 10.0分

*6*

使用jmeter进行测试时候，如果想知道采用器发送了什么数据给测试对象，应该怎么操作？

（10.0分）

- A、

  运行测试后，选择察看结果树，选择相应的结果项，点击“取样器结果”选项卡

- B、

  运行测试后，选择察看结果树，选择相应的结果项，点击“请求”选项卡

- C、

  运行测试后，选择察看结果树，选择相应的结果项，点击“响应数据”选项卡

正确答案： B 我的答案：B得分： 10.0分

*7*

正则表达式为：a.*b

字符串为：abcdefgab

第一次匹配的结果为



（15.0分）

- A、

  ab

- B、

  abcdefgab

正确答案： B 我的答案：B得分： 15.0分

## 二.多选题*（共2题,19.0分）*

*1*

下面哪些工具可以查看文档是否带有BOM签名

（10.0分）

- A、

  word

- B、

  UltraEdit

- C、

  Dreamweaver

- D、

  谷歌浏览器

正确答案： BC 我的答案：BC得分： 10.0分

*2*

要读取csv，可以

（9.0分）

- A、

  ![img](https://p.ananas.chaoxing.com/star3/origin/c8a03097c11a866161ca063c3d650dcc.png)

- B、

  ![img](https://p.ananas.chaoxing.com/star3/origin/31fffb8822476cd1de45932f67e9dd5f.png)

- C、

  ![img](https://p.ananas.chaoxing.com/star3/origin/d452de9ab0365b00595a2aa1d8e7c505.png)

- D、

  ![img](https://p.ananas.chaoxing.com/star3/origin/80749c1307708c5629c0ea03304ed67e.png)

正确答案： BC 我的答案：BC得分： 9.0分

## 三.判断题*（共1题,1.0分）*

*1*

下载“实验9.doc”并完成。完成后此题选择正确。

（1.0分）

我的答案：*√* 得分： 1.0分正确答案：*√*

答案解析：



![img](https://mooc1-1.chaoxing.com/js/editor20150812/dialogs/attachment_new/fileTypeImages/icon_default.gif)[9-第二题第1小题-成绩录入测试.jmx](https://mooc1-1.chaoxing.com/ueditorupload/read?objectId=120cb725947bdc15ae2776eecd5fd33f)

![img](https://mooc1-1.chaoxing.com/js/editor20150812/dialogs/attachment_new/fileTypeImages/icon_default.gif)[9-第二题第2小题-成绩录入测试(utf-8).jmx](https://mooc1-1.chaoxing.com/ueditorupload/read?objectId=854af04432d69720ca128a47c2e4cc4b)

![img](https://mooc1-1.chaoxing.com/js/editor20150812/dialogs/attachment_new/fileTypeImages/icon_default.gif)[9-第三题第3小题-显示班级信息.jmx](https://mooc1-1.chaoxing.com/ueditorupload/read?objectId=2d7728b729ff35f83fd0f892ca0a5362)

![img](https://mooc1-1.chaoxing.com/js/editor20150812/dialogs/attachment_new/fileTypeImages/icon_default.gif)[9-第三题第4小题-显示成绩&班级&专业信息.jmx](https://mooc1-1.chaoxing.com/ueditorupload/read?objectId=a7e526aa1051803a063d187b8a32820b)



- [第八课时作业](javascript:void(0))



## 一.单选题*（共10题,100.0分）*

*1*

﻿如果“demo8”部署后，成绩查询接口的地址是http://localhost/phptest/STest/demo8/getgrade.php

如果直接在浏览器上测试“demo8”的成绩查询接口，应该在浏览器输入

（10.0分）

- A、

  http://localhost/phptest/STest/demo8/getgrade.php

- B、

  http://localhost/phptest/STest/demo8/getgrade.php?xh=07120101

- C、

  http://localhost/phptest/STest/demo8/getgrade.php?xh=07120101$km=php

- D、

  http://localhost/phptest/STest/demo8/getgrade.php?xh=07120101&km=php

正确答案： D 我的答案：D得分： 10.0分

*2*

如果“demo8”部署后，成绩查询接口的地址是http://localhost/phptest/STest/demo8/getgrade.php如果直接在浏览器上输入http://localhost/phptest/STest/demo8/getgrade.php,结果会是

（10.0分）

- A、

  缺少学号入参

- B、

  缺少科目入参

- C、

  显示所有成绩

- D、

  缺少学号和科目入参

正确答案： A 我的答案：A得分： 10.0分

*3*

获取城市的城市代号的接口地址是http://toy1.weather.com.cn/search?cityname=参数，

现在要测试的城市是广州，那么再jemter相应的http请求元件的路径（如下图红色箭头处）要输入的内容是？

![img](https://p.ananas.chaoxing.com/star3/origin/dcefbd011368d1f16132f0e6b9b48c92.png)

（10.0分）

- A、

  

  [http://toy1.weather.com.cn/search?cityname=广州](http://toy1.weather.com.cn/search?cityname=参数，)

- B、

  

  [http://toy1.weather.com.cn](http://toy1.weather.com.cn/search?cityname=参数，)

- C、

  

  [toy1.weather.com.cn](http://toy1.weather.com.cn/search?cityname=参数，)

- D、

  

  [/search?cityname=广州](http://toy1.weather.com.cn/search?cityname=参数，)

正确答案： D 我的答案：D得分： 10.0分

*4*

如果只希望查看“登录”http请求元件的结果，那么察看结果树应该如何放置？

（10.0分）

- A、

  ![img](https://p.ananas.chaoxing.com/star3/origin/2e87dcf699bd511ea7eeda45a8b4530a.png)

- B、

  ![img](https://p.ananas.chaoxing.com/star3/origin/9b139b6aec3759b8f28dd374b4be6979.png)

- C、

  ![img](https://p.ananas.chaoxing.com/star3/origin/830ac565a2599fb5b814029fff1c4a75.png)

- D、

  ![img](https://p.ananas.chaoxing.com/star3/origin/775603bd392283050a83ad40c5eed588.png)

正确答案： A 我的答案：C得分： 0.0分

*5*

在jemter3.1中，要清除察看结果树的所有结果应该点击哪个按钮？

（10.0分）

- A、

  ![img](https://p.ananas.chaoxing.com/star3/origin/a9922f51b86b66e265b3f13a7160b49c.png)

- B、

  ![img](https://p.ananas.chaoxing.com/star3/origin/ecf4e6a0f7271d21fcc3bfaf85e2220c.png)

正确答案： A 我的答案：A得分： 10.0分

*6*

下图的察看结果树能查看的内容是

![img](https://p.ananas.chaoxing.com/star3/origin/6702bc5dfe5a8a025f8ea20d267bea99.png)

（10.0分）

- A、

  “登录”元件的结果

- B、

  “主页”元件的结果

- C、

  “登录”和“主页”元件的结果都可以看到

- D、

  “登录”和“主页”元件的结果都不可以看到

正确答案： C 我的答案：C得分： 10.0分

*7*

要测试本次课的web项目“demo8"里面的登录功能,下面参数配置正确的是？

（10.0分）

- A、

  ![img](https://p.ananas.chaoxing.com/star3/origin/5618a64bf4a1e3013bf66930f83cbc3f.png)

- B、

  ![img](https://p.ananas.chaoxing.com/star3/origin/a509334f46a1a431625ac1aefd404d34.png)

正确答案： A 我的答案：A得分： 10.0分

*8*

要测试本次课的web项目“demo8"里面的登录功能，应把用户名，密码等参数发到哪个php文件？

（10.0分）

- A、

  login.php

- B、

  logindo.php

- C、

  index.php

正确答案： B 我的答案：B得分： 10.0分

*9*

在jemter3.1中，要给线程组添加一个察看结果树，具体的操作过程是？

（10.0分）

- A、

  1、选择线程组，右击

  2、在弹出菜单选择“添加”

  3、选择“配置元件”

  4、选择"察看结果树"

  

- B、

  1、选择线程组，右击

  2、在弹出菜单选择“添加”

  3、选择“sampler”

  4、选择"察看结果树"

- C、

  1、选择线程组，右击

  2、在弹出菜单选择“添加”

  3、选择“监听器”

  4、选择"察看结果树"

正确答案： C 我的答案：B得分： 0.0分

*10*

在jemter3.1中，要添加一个http请求，具体的操作过程是？

（10.0分）

- A、

  1、选择线程组，右击

  2、在弹出菜单选择“添加”

  3、选择“配置元件”

  4、选择"http请求"

- B、

  1、选择线程组，右击

  2、在弹出菜单选择“添加”

  3、选择“sampler”

  4、选择"http请求"

  

- C、

  1、选择线程组，右击

  2、在弹出菜单选择“添加”

  3、选择“逻辑控制器”

  4、选择"http请求"

  

正确答案： B 我的答案：B





- [第七课时作业](javascript:void(0))



## 一.简答题*（共1题,100.0分）*

*1*

打开本次课资料目录下的"实验7.doc" 并完成。请把第五题“五、完成教材81页第6)题”的作答结果截图放入到答题框，如结果不止一页，按顺序截多张图。

（100.0分）

[正确答案：](javascript:void(0);)

略

我的答案：

![1.jpg](https://p.ananas.chaoxing.com/star3/origin/c5c4cb90e3ba36d040ae379678ecf8c2.jpg)![2.jpg](https://p.ananas.chaoxing.com/star3/origin/c1bf7f5af26488454d5fc9ebd2825269.jpg)![3.jpg](https://p.ananas.chaoxing.com/star3/origin/a2d3670a954057b72b10e067955ceee6.jpg)



- [第六课时作业](javascript:void(0))

## 一.单选题*（共6题,90.0分）*

*1*

如下因果图

![img](https://p.ananas.chaoxing.com/star3/origin/ef172ac3ca589066697c2c38924db2fa.png)

如想结果e1成立，那么C1,C2,C3的取值应该是

（15.0分）

- A、

  C1=1

  C2=1

  C3=1

- B、

  C1=0

  C2=0

  C3=0

  

- C、

  C1=1

  C2=0

  C3=1

  

- D、

  C1=1

  C2=1

  C3=0

  

正确答案： A 我的答案：A得分： 15.0分

*2*



使用因果图表示输入条件的约束。下图是E约束(异)

![img](https://p.ananas.chaoxing.com/star3/origin/fb3b8ded0ab491c29a02519c5b6390f5.png)

请问，使用1表示条件成立，0表示条件不成立，下面的哪个选项是不符合上图约束



（15.0分）

- A、

  a=0,b=0

- B、

  a=1,b=1

- C、

  a=1,b=0

- D、

  a=0,b=1

正确答案： B 我的答案：B得分： 15.0分

*3*

下图的判定表中，哪两列规划是可以合并成一列规则的？

![img](https://p.ananas.chaoxing.com/star3/origin/2b75d38d2d11c2cb9f4ef8bd48795f79.png)

（15.0分）

- A、

  1，2

- B、

  3，4

- C、

  2，3

- D、

  1，3

正确答案： D 我的答案：D得分： 15.0分

*4*

使用因果图表示输入条件的约束。下图是O约束(唯一)

![img](https://p.ananas.chaoxing.com/star3/origin/068fbf69c8fed3a58ee04f0e0c199ecd.png)

请问，使用1表示条件成立，0表示条件不成立，下面的哪个选项是符合上图约束

（15.0分）

- A、

  a=1，b=1

- B、

  a=0,b=0

- C、

  a=1,b=0

正确答案： C 我的答案：C得分： 15.0分

*5*


因果图中，![img](https://p.ananas.chaoxing.com/star3/origin/91b998aab2c4608478a7d463c1f331f7.png)这个符号表示

（15.0分）

- A、

  恒等

- B、

  与

- C、

  或

- D、

  非

正确答案： B 我的答案：B得分： 15.0分

*6*

因果图中，![img](https://p.ananas.chaoxing.com/star3/origin/a919b15cdad0f2d1a4df20283da07056.png)这个符号表示

（15.0分）

- A、

  恒等

- B、

  非

- C、

  或

- D、

  与

正确答案： C 我的答案：C得分： 15.0分

## 二.多选题*（共1题,9.0分）*

*1*

如下因果图

![img](https://p.ananas.chaoxing.com/star3/origin/cf52e63ad40a6e6a27dd0396e073b050.png)

如希望结果e1成立，那么C1,C2,C3的取值应该是

（9.0分）

- A、

  C1=0

  C2=0

  C3=1

- B、

  C1=0

  C2=1

  C3=1

- C、

  C1=1

  C2=1

  C3=1

- D、

  C1=0

  C2=0

  C3=0

正确答案： ABC 我的答案：ABC得分： 9.0分

## 三.判断题*（共1题,1.0分）*

*1*

下载“实验6.doc”，自行完成实验6。完成后，此题目选择正确即可。作业截止后，可以在本题的答案解析下载参考答案文件。

（1.0分）

我的答案：*√* 得分： 1.0分正确答案：*√*

答案解析：



![img](https://mooc1-1.chaoxing.com/js/editor20150812/dialogs/attachment_new/fileTypeImages/icon_doc.gif)[实验6-answer.doc](https://mooc1-1.chaoxing.com/ueditorupload/read?objectId=5b150825ebf207428a794730e85e9a76)



- [第五课时作业](javascript:void(0))



## 一.单选题*（共5题,40.0分）*

*1*

本次课计算保险的点数的例子中，如测试用例中，婚姻输入：离异，这是

（10.0分）

- A、

  有效等价类

- B、

  无效等价类

正确答案： B 我的答案：B得分： 10.0分

*2*

本次课计算保险的点数的例子中，如测试用例中，年龄输入100，这个是

（10.0分）

- A、

  有效等价类

- B、

  无效等价类

正确答案： B 我的答案：B得分： 10.0分

*3*

本次课的“相关代码”目录下，有我们课堂练习和实验5用到的java类代码，下面哪个类是用来计算保险费率的依据--点数

（5.0分）

- A、

  CheckDate.java

- B、

  Insurance_Rate.java

- C、

  Insurance_Rate_Cal.java

正确答案： C 我的答案：C得分： 5.0分

*4*

把本次课的“相关代码”目录下的Insurance_Rate.java和Insurance_Rate_Cal.java导入到你创建后的java项目，并运行。年龄输入 100，抚养人数输入 a。按下计算按钮，系统的反馈是

（5.0分）

- A、

  ![img](https://p.ananas.chaoxing.com/star3/origin/e157c889913887125760af3b9844fef1.png)

- B、

  ![img](https://p.ananas.chaoxing.com/star3/origin/e6c412e19bb76210bd1ca8828aef2f72.png)

- C、

  ![img](https://p.ananas.chaoxing.com/star3/origin/64abecda929d741f1156a2f476c2c666.png)

- D、

  ![img](https://p.ananas.chaoxing.com/star3/origin/ac1d23653455239a28088c245cf8db7b.png)

正确答案： C 我的答案：C得分： 5.0分

*5*

本次课计算保险的点数的例子中，如测试用例中，性别输入：女，这是

（10.0分）

- A、

  有效等价类

- B、

  无效等价类

正确答案： B 我的答案：B得分： 10.0分

## 二.多选题*（共5题,55.0分）*

*1*

规定日期由6位数字字符组成，前4位表示年，后2位表示月。如从输入日期值的类型和长度来看（不考虑输入值的年和月是否合理），下面一定是属于无效等价类的是

（15.0分）

- A、

  6位数字字符

- B、

  有非数字字符

  

  

- C、

  少于6位数字字符

  

  

- D、

  多于6位数字字符

正确答案： BCD 我的答案：BCD得分： 15.0分

*2*

下面说法正确的是

（15.0分）

- A、

  一个测试用例，应尽可能覆盖多个无效等价类

- B、

  一个测试用例，应尽可能覆盖多个有效等价类

- C、

  一个测试用例，应该只覆盖一个有效等价类

- D、

  一个测试用例，应该只覆盖一个无效等价类

正确答案： BD 我的答案：BD得分： 15.0分

*3*

把本次课的“相关代码”目录下的Insurance_Rate.java和Insurance_Rate_Cal.java导入到你创建后的java项目，并运行。用户可以输入或选择录入的内容

（5.0分）

- A、

  年龄

- B、

  性别

- C、

  保险费率

- D、

  婚姻

正确答案： ABD 我的答案：ABD得分： 5.0分

*4*

系统需求：每一个学生要选修1到3门的课程，下面属于无效等价类的是

（5.0分）

- A、

  选了1门课程

- B、

  选了3门课程

- C、

  没有选修课程

- D、

  选修了4门课程

正确答案： CD 我的答案：CD得分： 5.0分

*5*

需求是：成绩输入的范围是0到100之间的整数

根据边界值分析法，测试用例应该选

（15.0分）

- A、

  -10000

- B、

  0

- C、

  -1

- D、

  100

- E、

  99

正确答案： BCDE 我的答案：BCDE得分： 15.0分

## 三.判断题*（共1题,5.0分）*

*1*

1.自行完成本次课的课堂练习

本次课PPT的第15页“课堂练习：使用Junit辅助完成测试”

2.下载"实验5.doc"，自行完成实验5

3.课堂练习和实验5完成后，结果不用交。本题选正确即可，作业截止后。可以在答案解析那边下载参考答案。

（5.0分）

我的答案：*√* 得分： 5.0分正确答案：*√*

答案解析：

1.课堂练习的junit测试类

![img](https://mooc1-1.chaoxing.com/js/editor20150812/dialogs/attachment_new/fileTypeImages/icon_default.gif)[Insurance_Rate_CalTest.java](https://mooc1-1.chaoxing.com/ueditorupload/read?objectId=4947332e78e455119ba355807eec23ee)

2.实验5

![img](https://mooc1-1.chaoxing.com/js/editor20150812/dialogs/attachment_new/fileTypeImages/icon_doc.gif)[实验5.doc](https://mooc1-1.chaoxing.com/ueditorupload/read?objectId=f4bc2f831dd00eafd135e72355f1e415)





- [第四课时作业](javascript:void(0))

## 一.单选题*（共5题,95.0分）*

*1*

查看本次课的“课堂练习4.doc"，题目的代码有几个判定？

（10.0分）

- A、

  1

- B、

  2

- C、

  3

- D、

  4

正确答案： A 我的答案：A得分： 10.0分

*2*

查看本次课的“课堂练习4.doc"，题目的代码共有几个条件？

（10.0分）

- A、

  1

- B、

  2

- C、

  3

- D、

  4

正确答案： B 我的答案：B得分： 10.0分

*3*

查看本次课的“课堂练习4.doc"，下面哪个选项的测试用例符合条件覆盖标准？

（20.0分）

- A、

  a=100,b=100

  a=140,b=200

  a=90,b=300

- B、

  a=160,b=200

  a=180,b=100

- C、

  a=149,b=199

  a=150,b=200

- D、

  a=149,b=199

  a=140,b=200

正确答案： C 我的答案：C得分： 20.0分

*4*

查看本次课的“课堂练习4.doc"，下面哪个选项的测试用例符合判定覆盖标准？

（25.0分）

- A、

  a=150,b=200

- B、

  a=150,b=200

  a=149,b=200

- C、

  a=100,b=200

  a=150,b=199

- D、

  a=200,b=100

  a=150,b=199

  

正确答案： B 我的答案：B得分： 25.0分

*5*

查看本次课的“课堂练习4.doc"，下面哪个选项的测试用例符合判定-条件覆盖标准？

（30.0分）

- A、

  a=100,b=199

  a=150,b=200

- B、

  a=100,b=199

  a=100,b=200

  

- C、

  a=200,b=200

  a=150,b=200

  

正确答案： A 我的答案：A得分： 30.0分

## 二.判断题*（共1题,5.0分）*

*1*

请自行完成本次课的实验4和课堂练习，结果无需上传。完成后，本题选正确即可。

（5.0分）

我的答案：*√* 得分： 5.0分正确答案：*√*

答案解析：

![img](https://mooc1-1.chaoxing.com/js/editor20150812/dialogs/attachment_new/fileTypeImages/icon_doc.gif)[课堂练习4.doc](https://mooc1-1.chaoxing.com/ueditorupload/read?objectId=ce080c8a145251895ac5cc52335532a7)

![img](https://mooc1-1.chaoxing.com/js/editor20150812/dialogs/attachment_new/fileTypeImages/icon_ppt.gif)[课堂练习4讲解.ppt](https://mooc1-1.chaoxing.com/ueditorupload/read?objectId=24a3401ddba2d5ffb09d0597fc3c43f9)

![img](https://mooc1-1.chaoxing.com/js/editor20150812/dialogs/attachment_new/fileTypeImages/icon_doc.gif)[实验4.doc](https://mooc1-1.chaoxing.com/ueditorupload/read?objectId=038c567a02604af716eea86daca7641a)





- [第三课时作业](javascript:void(0))



## 一.单选题*（共4题,60.0分）*

*1*

要测试web系统的退出功能是否正常，下面那一项的测试步骤是正确的？

（15.0分）

- A、

  点击退出，系统能显示退出成功，并且跳转到登录页面，那么退出功能正常。

- B、

  点击退出，系统显示提出成功。然后再尝试直接从浏览器的地址栏输入登录成功后的任意一个功能的地址，如能正常进入，那么，退出功能正常。

- C、

  点击退出，系统显示提出成功。然后再尝试直接从浏览器的地址栏输入登录成功后的任意一个功能的地址，如能正常进入，那么，退出功能不正常。有bug。

- D、

  点击退出，系统显示提出成功。那么退出功能正常。

正确答案： C 我的答案：C得分： 15.0分

*2*

下面的gif动画是测试员工总数录入文本框。动画测试了哪几项内容？

![web组件-文本框测试~1.gif](https://p.ananas.chaoxing.com/star3/origin/5ca636cecae4afd83786eb49521d5227.gif)

（15.0分）

- A、

  是否可以为空、是否可以输入非整数、是否能通过复制的方法输入非整数。是否能通过sql注入

- B、

  是否可以为空、是否可以输入非整数、是否能通过复制的方法输入非整数

- C、

  是否可以为空、是否可以输入中文、是否能通过复制的方法输入非整数

- D、

  是否可以输入非整数、是否能通过复制的方法输入非整数

正确答案： B 我的答案：A得分： 0.0分

答案解析：

注意，C选项和B很接近，区别是,B选项.内容是“...是否可以输入非整数...." C选项内容是“...是否可以输入中文...." 。非整数包括 中文，小数，字母，特殊符合等等

*3*

运行windows程序，出现了如下的错误提示，是因为

![img](https://p.ananas.chaoxing.com/star3/origin/04ded2b518348accd1e487ddff281cd4.png)

（15.0分）

- A、

  windows系统缺少Framework3.5

- B、

  windows系统缺少Framework4.0

- C、

  windows系统缺少Framework2.0

- D、

  windows系统缺少Framework1.0

正确答案： B 我的答案：B得分： 15.0分

*4*

语句覆盖，判定覆盖和条件覆盖的标准分别是什么？

（15.0分）

- A、

  语句覆盖：使得程序中每个判定至少为TRUE或FALSE各一次

  判定覆盖：使得程序中每个语句至少都能被执行一次

  条件覆盖：得每个判定中的每个条件获得各种可能的结果

- B、

  语句覆盖：使得程序中每个语句至少都能被执行一次

  判定覆盖：使得程序中每个判定至少为TRUE或FALSE各一次

  条件覆盖：得每个判定中的每个条件获得各种可能的结果

  

- C、

  语句覆盖：得每个判定中的每个条件获得各种可能的结果

  判定覆盖：使得程序中每个判定至少为TRUE或FALSE各一次

  条件覆盖：使得程序中每个语句至少都能被执行一次

  

- D、

  语句覆盖：得每个判定中的每个条件获得各种可能的结果

  判定覆盖：使得程序中每个语句至少都能被执行一次

  条件覆盖：使得程序中每个判定至少为TRUE或FALSE各一次

  

正确答案： B 我的答案：B得分： 15.0分

## 二.多选题*（共1题,25.0分）*

*1*

下面，属于白盒测试的覆盖标准的是？

（25.0分）

- A、

  语句覆盖

- B、

  判定覆盖

- C、

  逻辑覆盖

- D、

  条件覆盖

- E、

  选择覆盖

- F、

  判定条件覆盖

- G、

  条件组合覆盖

正确答案： ABDFG 我的答案：ABDFG得分： 25.0分

## 三.简答题*（共1题,15.0分）*

*1*

在本次课程对应的资料目录下下载"实验3.doc"文档和相关文件，完成实验3。把第一题“编写个人所得税计算类”完成后的CalTax.java文件代码复制到下面（注意：是把代码的文本复制到答题框，不是上传代码文件，否则，不给分）。第二题不用复制，自行完成。

（15.0分）

[正确答案：](javascript:void(0);)

//计算个人所得税
public class CalTax {
   public double cal(double sq,double sb){
     double r = 0;
     double c = sq -sb-5000;
     double sl = 0; //税率
     double sx = 0;//速算扣除数
     if(c<=0){
       r = 0;
     }else{
       if(c<=36000){
         sl = 0.03;
         sx = 0;
       }else if(c<=144000){
         sl = 0.1;
         sx = 2520;
         

       }
       else if(c<=300000){
         sl = 0.2;
         sx = 16920;
         
       }
       else if(c<=420000){
         sl = 0.25;
         sx = 31920;
         
       }
       else if(c<=660000){
         sl = 30;
         sx = 52920;
         
       }
       else if(c<=960000){
         sl = 0.35;
         sx = 85920;
         
       }
       else {
         sl = 0.45;
         sx = 181920;
         
       }
       r = c*sl-sx;
       
     }
     return r;

   }

}



我的答案：

import java.util.ArrayList;
/** * @author moreant * @date 2020/03/22 15:51 * 在线版: https://paste.ubuntu.com/p/yCvjhNmT7f/ */public class CalTax {  /**   * 计算缴税款   * @param bTax 税前工资   * @param tsb 各项社会保险费及扣除   * @return 应缴税款   */  private Double cal(Double bTax, Double tsb) {    if (bTax > 5000) {      bTax -= 5000-tsb;      int i = 0;      for (Double tmp = bTax; tmp > 36000; i++) {        tmp -= obj.get(i + 1).getWithholding();      }      // 应纳个人所得税税额= 应纳税所得额× 适用税率- 速算扣除数      System.out.println(bTax * obj.get(i).getWithholdingRate() - obj.get(i).getQuickDeductions());    }    return 0.0;  }
  ArrayList<Tex> obj = new ArrayList<Tex>() {    {      add(new Tex(5000, 0.03, 0));      add(new Tex(36000, 0.1, 2520));      add(new Tex(144000, 0.20, 16920));      add(new Tex(300000, 0.25, 31920));      add(new Tex(420000, 0.30, 52920));      add(new Tex(660000, 0.35, 85920));      add(new Tex(960000, 0.45, 181920));    }  };
  static class Tex {    // 预扣额    private final Integer withholding;    // 预扣率    private final Double withholdingRate;    // 速算扣除数    private final Integer quickDeductions;
    public Tex(Integer withholding, Double withholdingRate, Integer quickDeductions) {      this.withholding = withholding;      this.withholdingRate = withholdingRate;      this.quickDeductions = quickDeductions;    }
    public Integer getWithholding() {      return withholding;    }
    public Double getWithholdingRate() {      return withholdingRate;    }
    public Integer getQuickDeductions() {      return quickDeductions;    }  }}

批语

回答错误





- [第二课时作业](javascript:void(0))

## 一.单选题*（共3题,70.0分）*

*1*

Junit具体是通过哪个函数判断期望值和测试值是否一致的？

（20.0分）

- A、

  assert

- B、

  equals

- C、

  setUp

- D、

  assertEquals

正确答案： D 我的答案：D得分： 20.0分

*2*

CalArea类的CircularArea方法是计算圆的面积。入参是圆的半径。

public class CalArea {  
   public double CircularArea(double r){
     r = 3.14*r*r;
     return r;
   }

  ........ 
}

在测试类里面测试这个方法,假设圆的半径为2，请正确补全下面的代码

public class CalAreaTest {
   private CalArea calArea = new CalArea();
   @Test
   public void testCircularArea() {  
        //此处填写测试代码
   }

 .......

}

（30.0分）

- A、

  assertEquals(12.56,calArea.CircularArea(2));

- B、

  assertEquals(2,calArea.CircularArea(12.56));

- C、

  assertEquals(12.56,calArea.CircularArea(2),0.01);

正确答案： C 我的答案：C得分： 30.0分

*3*

运行Junit测试后，以下部分结果的截图

![img](https://p.ananas.chaoxing.com/star3/origin/cf2eac8e04bc084a7017d33562dc7045.png)

下面描述正确的是？

（20.0分）

- A、

  testSubstract方法：程序异常

  testDivide方法：结果和期望值不一致

  testMultiply方法：此方法被忽略，测试时并未执行

- B、

  testSubstract方法：结果和期望值不一致

  testDivide方法：程序异常

  testMultiply方法：此方法被忽略，测试时并未执行

  

- C、

  testSubstract方法：结果和期望值不一致

  testDivide方法：此方法被忽略，测试时并未执行

  testMultiply方法：程序异常

  

- D、

  testSubstract方法：程序异常

  testDivide方法：此方法被忽略，测试时并未执行

  testMultiply方法：结果和期望值不一致

  

正确答案： B 我的答案：B得分： 20.0分

## 二.多选题*（共1题,20.0分）*

*1*

想给项目添加Junit Libraries 接下来可以选择的菜单项有
![img](https://p.ananas.chaoxing.com/star3/origin/35d5aab4e2f3c41f554bc4a82d3968a9.png)

（20.0分）

- A、

  New

- B、

  Build Path

- C、

  Import

- D、

  Properties

正确答案： BD 我的答案：BD得分： 20.0分

## 三.判断题*（共2题,10.0分）*

*1*

使用Junit测试时候，如果在测试方法前加@Ignore，表示执行测试时候，此方法将被忽略。

（9.0分）

我的答案：*√* 得分： 9.0分正确答案：*√*

*2*

请自觉完成本次课的“实验2”。结果不用上传，完成后本题目选择“正确”。

（1.0分）

我的答案：*√* 得分： 1.0分正确答案：*√*

答案解析：

![img](https://mooc1-1.chaoxing.com/js/editor20150812/dialogs/attachment_new/fileTypeImages/icon_default.gif)[CalArea.java](https://mooc1-1.chaoxing.com/ueditorupload/read?objectId=d4fa90af7a11cef50e1047cd008c8028)

![img](https://mooc1-1.chaoxing.com/js/editor20150812/dialogs/attachment_new/fileTypeImages/icon_default.gif)[CalAreaTest.java](https://mooc1-1.chaoxing.com/ueditorupload/read?objectId=53784aba620b8b1c80630c28f46feaa0)

![img](https://mooc1-1.chaoxing.com/js/editor20150812/dialogs/attachment_new/fileTypeImages/icon_default.gif)[Calculator.java](https://mooc1-1.chaoxing.com/ueditorupload/read?objectId=c3d8db3527e608534ed1aebccf67339e)

![img](https://mooc1-1.chaoxing.com/js/editor20150812/dialogs/attachment_new/fileTypeImages/icon_default.gif)[CalculatorTest.java](https://mooc1-1.chaoxing.com/ueditorupload/read?objectId=2b2ed3c33be0c2a9234c57e3351c5d86)



[第一课时作业](javascript:void(0))

| 客观 成绩 | 单选题 （30.0分） |
| --------- | ----------------- |
| 30.0      |                   |

| 客观总分 |
| -------- |
| 30.0     |

| 主观 成绩 | 填空题 （20.0分） | 简答题 （45.0分） |
| --------- | ----------------- | ----------------- |
| 20.0      | 45.0              |                   |

| 主观总分 |
| -------- |
| 65.0     |

### 总得分

95.0

## 一.单选题*（共2题,30.0分）*

*1*

在部署本次课的“成绩管理系统-WEB”项目的时候（解压本次课对应的资料目录下的“要测试程序.rar“文件的"成绩管理系统-WEB.rar"文件即可得到项目代码文件）。如果直接用“成绩管理系统-WEB”作为目录名，放在apache可以解析的web目录下，然后启动项目，访问项目根目录下的index.php文件，将会

（15.0分）

- A、

  只要web环境部署正确，php版本符合要求，能正常运行

- B、

  会出现如“

  Warning: Unknown: failed to open stream: No such file or directory in Unknown on line 0“的错误，如下图：

  ![img](https://p.ananas.chaoxing.com/star3/origin/fbab9a50a2d0a08467ede62e5265b984.png)

  的错误，因为apache解析中文目录下的php文件会有错误

- C、

  会有PHP版本不符合要求的提示

正确答案： B 我的答案：B得分： 15.0分

*2*

在部署本次课的“成绩管理系统-WEB”项目的时候。如出现“

Fatal error: Uncaught Error: Call to undefined function mysql_connect() ...”错误，原因是

（15.0分）

- A、

  数据库mysql用户名或密码错误，或者mysql数据库程序没有启动成功

- B、

  web目录包含中文名

- C、

  php版本是7.0或以上，而mysql_connect()函数已经被废弃

正确答案： C 我的答案：C得分： 15.0分

## 二.填空题*（共1题,20.0分）*

*1*

解压本次课对应资料目录下的“要测试程序.rar“文件。在“桌面程序”目录下找到"SFTest（bug）.exe"文件，运行。请尝试输入用户名_________________和密码_________________成功注入

（20.0分）

[正确答案：](javascript:void(0))

*第一空：* 1' or '1'='1
*第二空：* 1' or '1'='1

我的答案：得分： 20.0分

*第一空：* 

任意![GIF.gif](https://p.ananas.chaoxing.com/star3/origin/cd333b6d4913fca466911455b80c05ba.gif)

*第二空：* 

‘ or '1' = 1

批语

回答正确

## 三.简答题*（共2题,45.0分）*

*1*

在资料目录下找到本次课的资料目录，下载“实验1.doc”完成实验1。

把两道题目要求填写的表格填写完毕后，复制到下面





（20.0分）

[正确答案：](javascript:void(0);)

略



我的答案：

一、测试桌面应用程序的登录功能测试人员操作预期结果软件反应输入合法的用户名和密码成功进入成功进入输入合法的用户名和不合法密码不可以进入，并给出合理的提示不可以进入，并给出合理的提示输入不合法的用户名和正确密码不可以进入，并给出合理的提示不可以进入，并给出合理的提示输入不合法的用户名和不正确的密码不可以进入，并给出合理的提示不可以进入，并给出合理的提示输入 SQL 注入语句不可用进入，并给出合理提示成功进入
二、测试Web 应用程序测试人员操作预期结果软件反应输入合法的用户名和密码成功进入成功进入输入合法的用户名和不合法密码不可以进入，并给出合理的提示不可以进入，并给出合理的提示输入不合法的用户名和正确密码不可以进入，并给出合理的提示不可以进入，并给出合理的提示输入不合法的用户名和不正确的密码不可以进入，并给出合理的提示不可以进入，并给出合理的提示
输入 SQL 注入语句不可用进入，并给出合理提示成功进入





*2*

本次课对应资料目录下的“要测试程序.rar“文件。“桌面程序”进入系统后，显示的都是“已收费”的记录。现在想测试一下对未收费的记录进行收费。你有什么办法

1、请说出你的思路。

2、如果你能实现此功能，请截取运行软件时，出现的包含未收费记录的界面或者点击确认收费按钮，提示收费成功的界面。

（25.0分）

[正确答案：](javascript:void(0);)

安装access编辑工具，进入access修改相应表的记录

我的答案：

在数据库中添加一条未收费的假数据进行测试。"未收费" 是否能确认收费， "收费" 是否能确认收费，"已收费2" 是否能确认收费![Snipaste_2020-03-12_20-47-16.png](https://p.ananas.chaoxing.com/star3/origin/0a6b3cae25e465ebaf9ee5b9b64983cf.png)![Snipaste_2020-03-12_20-47-49.png](https://p.ananas.chaoxing.com/star3/origin/7f75f22eba7ea4e01c91d7344e4de73b.png)![Snipaste_2020-03-12_20-47-25.png](https://p.ananas.chaoxing.com/star3/origin/4dc403e6f0b524a57baaefe2702feddd.png)![Snipaste_2020-03-12_20-48-07.png](https://p.ananas.chaoxing.com/star3/origin/b83a9fc7316adbb2942f2b050e07059e.png)

















随堂练习

03-11 11:47

\1. [多选题]

我们这门课程主要的学习内容有？





A.

软件测试





B.

代码安全





C.

java程序设计





D.

Laravel



正确答案：AB

\2. [多选题]

常见的软件架构有





A.

B/S





B.

C/S





C.

W/S





D.

Q/S



正确答案：AB

\3. [多选题]

下面属于数据库软件的是？





A.

vmware





B.

sqlite







C.

foxpro







D.

access





正确答案：BCD

\4. [单选题]

第一课时作业中，我们要测试两种类型的程序，其中，桌面端程序里面使用了什么数据库？





A.

access





B.

sqlite





C.

db





D.

sqlserver



正确答案：A

\5. [单选题]

第一课时作业中，我们要测试两种类型的程序，其中，web成绩管理程序需要PHP的版本是？





A.

PHP7.0或以上





B.

低于PHP7.0的版本



正确答案：B















第二课时测验

03-13 11:53

\1. [单选题]

Java用于测试的包的名称叫？





A.

junit





B.

jtest





C.

calculator



正确答案：A

\2. [单选题]

上课演示的Junit的版本是





A.

junit3





B.

junit4





C.

junit5



正确答案：B

\3. [单选题]

测试用例的设计的重要参考文档是？





A.

测试报告





B.

测试总结





C.

需求分析





D.

测试方案



正确答案：C









第四课时小测

03-20 12:07

\1. [多选题]

今天我们学习了白盒测试的那几种覆盖标准？





A.

语句覆盖





B.

判定覆盖





C.

条件覆盖





D.

判定条件覆盖





E.

条件组合覆盖





F.

路径覆盖



正确答案：DEF

\2. [单选题]

语句覆盖、判定覆盖、条件组合覆盖、路径覆盖这及格覆盖标准从弱到强的排序是？





A.

语句覆盖、判定覆盖、条件组合覆盖、路径覆盖





B.

路径覆盖、判定覆盖、条件组合覆盖、语句覆盖





C.

路径覆盖、条件组合覆盖、判定覆盖、语句覆盖



正确答案：A

\3. [单选题]

执行足够的测试用例，使得判定中每个条件取到各种可能的值，并使每个判定取到各种可能的结果。这个是白盒测试中的什么覆盖标准？





A.

判定覆盖





B.

条件覆盖





C.

条件组合覆盖





D.

判定-条件覆盖



正确答案：D

\4. [单选题]

执行足够的例子，覆盖程序中所有可能的路径。这是白盒测试中的什么覆盖标准？





A.

路径覆盖





B.

判定覆盖





C.

条件组合覆盖



正确答案：A







第四课时小测

03-25 12:00

\1. [多选题]

本次课讲解了那几种黑盒测试方法





A.

场景法





B.

等价类划分





C.

边界值分析





D.

错误推测





E.

判定覆盖



正确答案：BCD

\2. [多选题]

等价类分为





A.

有效等价类





B.

无效等价类





C.

一般等价类





D.

特殊等价类



正确答案：AB

\3. [多选题]

要求成绩的值的范围是0--100的整数，使用边界值分析法进行测试用例设计，下面应该选的值是





A.

0





B.

100





C.

99





D.

-1





E.

100000





F.

-19999



正确答案：ABCD















第六课时小测

03-27 12:01

\1. [单选题]

![img](data:image/png;base64,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)

上面的图形表示因果图的







A.

恒等





B.

非





C.

或





D.

与



正确答案：C

\2. [单选题]

下面哪个图形是表示唯一约束





A.

![img](data:image/png;base64,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)





B.

![img](data:image/png;base64,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)





C.

![img](data:image/png;base64,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)





D.

![img](data:image/png;base64,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)



正确答案：B

\3. [单选题]

在绘制判定表的时候，如果条件有三个，那么条件的组合有几种？





A.

8





B.

3





C.

4





D.

6



正确答案：A







第七课时小测

04-01 11:56

\1. [多选题]

本次课讲述的场景法的例子中，属于基本流的是操作步骤的是





A.

插入卡





B.

账户无效





C.

取款成功





D.

密码错误



正确答案：AC

\2. [多选题]

本次课在测试demo7里面的成绩查询接口getgrade.php的时候，需要的入参包括





A.

xh





B.

km





C.

cj





D.

xm



正确答案：AB

\3. [单选题]

在jmeter中，要查看http请求元件的结果，需要添加





A.

HTTP信息头管理器





B.

HTTP Cookie 管理器





C.

察看结果树





D.

HTML链接解析器



正确答案：C

\4. [单选题]

本次课在使用jmeter测试demo7里面的成绩查询接口getgrade.php的时候。下图的红色箭头处，应该选

![img](data:image/png;base64,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)





A.

get





B.

post





C.

put



正确答案：A





八课时小测

04-03 12:21

\1. [单选题]

下图是一个正则表达式提取器，如在其他地方引用提取器提出来的值，应该如何引用

![img](data:image/png;base64,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)







A.

citycode





B.

$citycode





C.

${citycode}





D.

{citycode}



正确答案：C

\2. [单选题]

要把badboy录制的脚本导出为jmeter能读取的格式，应该如何操作





A.

选择菜单 File --->Export to Jmeter..





B.

选择菜单 File --->Save.





C.

选择菜单 File --->Save.as



正确答案：A

\3. [单选题]

下面是一个正则表达式

<td>.*<\/td>

要匹配的对象字符串是

<table><tr><td>成绩</td><td>科目</td></tr></table>

那么，第1个匹配到的结果是







A.

<td>成绩</td>





B.

<td>成绩</td><td>科目</td>





C.

<table><tr><td>成绩</td><td>科目</td></tr></table>



正确答案：B

\4. [单选题]

下面是一个正则表达式

<td>.*?<\/td>

要匹配的对象字符串是

<table><tr><td>成绩</td><td>科目</td></tr></table>

那么，第1个匹配到的结果是





A.

<td>成绩</td>





B.

<td>成绩</td><td>科目</td>





C.

<table><tr><td>成绩</td><td>科目</td></tr></table>



正确答案：A







第九课时小测

04-08 11:56

\1. [多选题]

如何查看文件是否包含BOM签名





A.

用UltraEdit打开文件，切换到十六进制编辑模式，察看文件头部是否有EF BB BF





B.

用Dreamweaver打开，察看页面属性，看“包括Unicode签名BOM”前面是否有个勾



正确答案：AB

\2. [多选题]

如何去除BOM签名？





A.

用Dreamweaver打开，点击文件—另存为，把“包括Unicode签名BOM”前面是的勾去掉





B.

sublime text打开文件，然后选择菜单File—>Save with Encoding -> UTF-8





C.

使用notepad++打开文件---点击编码---转为UTF-8编码---然后保存即可



正确答案：ABC

\3. [单选题]

对中文进行url编码,要编码的中文是: 你好

格式是gb2312,编码后的内容是

（可以使用在线工具，http://tool.chinaz.com/tools/urlencode.aspx）





A.

%c4%e3%ba%c3





B.

%e4%bd%a0%e5%a5%bd



正确答案：A







第十课时小测

04-10 11:55

\1. [判断题]

下图红色箭头的正则表式也可以这样写：<td>(.+?)<\/td>

![img](data:image/png;base64,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)





1.对



2.错

正确答案：对

\2. [单选题]

在jmeter中，如果希望查看变量的值，需要添加





A.

计数器





B.

查看结果树





C.

Debug Sampler



正确答案：C

\3. [多选题]

jmeter如需要测试数据库，必需先安装相应jar包。安装方法可以是





A.

点击测试计划，测试计划最下方的add directory or jar to classpath，添加下载的jar





B.

将下载的jar文件放置于jmeter安装目录的 \lib\ext目录内





C.

将下载的jar文件放置于jmeter安装目录的 \lib目录内



正确答案：ABC

\4. [单选题]

如果使用jmeter连接数据库

服务器的地址为192.168.0.1

数据库名称为：demo9

端口为：3306

编码为:utf-8

那么，JDBC Connection Configuration 元件的DataBaseURL参数应该怎么填







A.

jdbc:mysql://192.168.0.1/3306/demo9





B.

jdbc:mysql://192.168.0.1/3306/demo9/characterEncoding=utf-8





C.

jdbc:mysql://192.168.0.1:3306/demo9?characterEncoding=utf-8



正确答案：C



\1. [单选题]

proc_showgrade是sqlserver里面的一个存储过程，没有入参，现在想在jmeter的jdbc请求元件中调用它，下面配置正确的是





A.

![img](data:image/png;base64,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)





B.

![img](data:image/png;base64,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)





C.

![img](data:image/png;base64,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)





D.

![img](data:image/png;base64,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)



正确答案：C

\2. [单选题]

要删除成绩表tb_grade的所有数据，下面配置正确的是





A.

![img](data:image/png;base64,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)





B.

![img](data:image/png;base64,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)





C.

![img](data:image/png;base64,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)



正确答案：A

\3. [单选题]

如希望测试计划的线程组按顺序从上到下执行，如下图

![img](data:image/png;base64,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)

执行顺序是线程组1，线程组2，线程组3。下面配置测试计划正确的是





A.

![img](data:image/png;base64,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)





B.

![img](data:image/png;base64,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)





C.

![img](data:image/png;base64,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)



正确答案：B





\1. [单选题]

ftp的匿名用户的用户名是





A.

anonymous





B.

admin





C.

user





D.

users



正确答案：A

\2. [单选题]

![img](md_img/66b1428e310f1d2a6a64201b251943ab.png)

上图是FileZillaServer用户的目录设置，哪个是根目录？







A.

E:\javacode





B.

D:\PHP



正确答案：B

\3. [单选题]

在jmeter中配置“FTP请求"采样器元件匿名访问ftp服务器。用户名如何配置？





A.

不用填写





B.

填写anonymous





C.

填写user





D.

填写admin



正确答案：B



