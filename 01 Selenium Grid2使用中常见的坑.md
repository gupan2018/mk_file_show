---
title: 01 Selenium Grid2使用中常见的坑
tags: 新建,模板,小书匠
grammar_cjkRuby: true
---

# <font size='6' ><font color='red'>**1.**</font> 做分布式自动化测试时远程机报错</font>

```python
selenium.common.exceptions.WebDriverException: Message: unknown error: call function result missing 'value'
  (Session info: chrome=65.0.3325.181)
  (Driver info: chromedriver=2.30.477700 (0057494ad8732195794a7b32078424f92a5fce41),platform=Windows NT 6.1.7601 SP1 x86_64)
```
<font size='4' color='red'>**错误原因:**</font>谷歌浏览器webdriver没有对应
