# Nessus-html-CSV
根据https://github.com/Bypass007/Nessus_to_report
大佬的GitHub项目进行更改，大佬的中文数据库打开有乱码，我对数据库进行utf-8重新编写。
1、Nessus扫描结束，选择HTML类型，Report选择Custom，Croup By 选择Host，导出HTML报告。 

2、运行脚本： Nessus_resport.py test.html 

运行过程截图：


最终，同目录下，生成CSV文件，包含服务器IP、漏洞名称、风险级别、漏洞描述、修复建议。


参考资料：

中文漏洞库：https://github.com/FunnyKun/NessusReportInChinese

Bypass
