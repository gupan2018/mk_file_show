---
title: 01 Selenium使用中常见的坑
tags: 新建,模板,小书匠
grammar_cjkRuby: true
---
# <font id="1" size='6' face='黑体'><font color='red'>**目录**</font></br>

&nbsp;&nbsp;<a href="#1"><font size="4" face="宋体">1. 运行脚本过程中报：call function result</font></a>

# 01 Selenium Grid2使用中常见的坑
<font id="1" size='6' face='黑体'>
<font color='red'>1.1</font> 
做分布式自动化测试时远程机报错
</font></br>

```python
selenium.common.exceptions.WebDriverException: Message: unknown error: call function result missing 'value'
  (Session info: chrome=65.0.3325.181)
  (Driver info: chromedriver=2.30.477700 (0057494ad8732195794a7b32078424f92a5fce41),platform=Windows NT 6.1.7601 SP1 x86_64)
```
**<font size='5' color='red' face="黑体">错误原因:</font>**
&nbsp;&nbsp;<font size="4">谷歌浏览器webdriver没有对应</font>
<font size='5' color='#000066' face='黑体'>**chromdriver与谷歌浏览器版本对应详解：**</font>
&nbsp;&nbsp;<font size='4' face="楷体">https://blog.csdn.net/huilan_same/article/details/51896672</font>


