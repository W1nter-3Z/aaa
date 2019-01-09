### gitbook数据提取

1、文件目录

+ exports
  +  revision.json
  + Space.json
  + versions
    + master
      + pages（各个页面导出的json文件）
+ getPdf.py

2、环境需求

+ python 3.6  PyPDF2  pdfkit

3、方法

+ 获取导出目录下各级信息 revison的标题简称信息 pages的详情信息
+ 处理信息 换行 空白 
+ 生成目录信息和内容信息的列表
+ 生成字符串
+ 调用pdfkit strtopdf方法
+ 处理pdf合成的顺序
+ 调用PYPDF2 的方法 构造MergePdf方法 合成pdf

4、结果

+ ./outpdfs/out1.pdf