### 1. Domain's DNS record could not be retrieved

 > 可以把将域名理解为一个人的姓名，IP地址理解为身份证号，一般来说姓名和身份证号是对应的。对于计算机来说更喜欢存储身份证号，我们则更擅长记忆名字。IP地址是网络上标识用户站点的数字地址，为了简单好记，采用域名来代替IP地址表示网站地址，域名服务器（DNS）将域名解析成IP地址，使之一一对应。
 
 > 如果你用github充当主机，setting中显示 “Domain's DNS record could not be retrieved. ”，你要做的就是: 
 >>     1.确保github 的库中的CNAME，域名没有写错。deepious.top即可，不要写成www.deep.ious
 
 >>     2. 检查域名解析设置中的三个设置是否都在

 >>     3. 查看当前的域名服务是否正常。
 
 #### ***不过我觉得比较重要的一点是需要有耐心，有时候服务器崩溃，有时候要等很长时间***
