
# 方法：PclZip::merge
英文原文：http://www.phpconcept.net/pclzip/user-guide/59

## 概述
本方法用于将另一个压缩包内的所有内容合并到当前压缩包中。

（PclZip >= 1.2）


## 用法
```php
PclZip::merge($archive_filename)
```



## 参数
- $archive_filename：将要被合并的压缩包名（被合并到当前对象的压缩包中）



## 返回值
- 0：出现错误
- 1：合并成功



## 描述
本方法用于将另一个压缩包内（`$archive_filename`参数）的所有内容合并到当前对象的压缩包中。

合并过程中，并不会进行任何检查，如不会检查同名的文件。

本方法不是一个更新压缩包功能的函数，本方法只是一个很无脑的合并。



