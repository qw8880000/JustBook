
cloc 是一个统计代码行数的工具，可以方便统计各种不同代码类型。

# 在ubuntu下安装

`sudo apt-get install cloc`

# 用法

例如使用`cloc ./wordpress` 查看我的wordpress代码行数，输出如下：
```
-------------------------------------------------------------------------------
Language                     files          blank        comment           code
-------------------------------------------------------------------------------
Javascript                     453          48051          66556         229455
PHP                            741          42304         123357         191921
CSS                            225          17335           4984          92424
SASS                            53           1233            497           4554
HTML                             1             13              0             86
XML                              1              6              0             37
-------------------------------------------------------------------------------
SUM:                          1474         108942         195394         518477
-------------------------------------------------------------------------------
```
