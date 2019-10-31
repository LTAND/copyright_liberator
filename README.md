# About

软著救星帮你从指定的工程目录下拷贝所有的代码，并尽力避开名称与日期相关的注释后输出到指定 word 文档。

### v1.0 生成的 word 样式

|字体|字号|其他|备注|
|--|--|--|--|
|宋体|5号|无|无|


# Version

**Version 1.0**  

- 支持核心功能
- 支持指定复数个工程目录

# Features

有可能有也有可能没有。

# Environment

|环境|版本|支持|备注|
|--|--|--|--|
|操作系统|全平台|是|无|
|python|python3.44|是|>=python3.7|


# How to work

1. 在本机安装好 >=python3.7 运行环境。
2. 按照示例中的方式，指定参数后运行 tool.py 文件。
3. 修改 tool.py 中的配置可以支持其他字体和样式。

### example for work
```shell
# 提前安装相关依赖
pip3 install python-docx

# 执行脚本
python3 tool.py ${word文档生成的路径} ${项目工程路径1,项目工程路径1} ${页眉名称(不要漏掉\t符号)}

# 示例
python3 tool.py /Users/**/copyright-tool/copyright.docx /Users/**/channel-server,/Users/job-server \t统一支付平台


```

# 其他

- 请养成先 star 再使用的好习惯。
- 如果需要更多的样式或功能支持请扫码支付 -> 
https://www.gitbook.com/book/mikumikulch/chucklin_blog 
价格随缘即可。

项目严格遵守 [MIT License](https://choosealicense.com/licenses/mit/) 。你可以在署名原作者的情况下采用任何方式使用本代码，
但原作者不承担代码使用后的风险，也没有技术支持的义务。
