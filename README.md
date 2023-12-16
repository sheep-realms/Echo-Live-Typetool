# Echo-Live-Typetool
使用C++编写的一个输入工具，适用于Echo-Live
Echo-Live项目地址：https://github.com/sheep-realms/Echo-Live
#如何使用？
将Typetool.exe复制到start.js的同一目录下，在cmd或者powershell等终端中使用命令行来启动此控制台程序
```./Typetool.exe```
#注意事项
1.请确保你的终端编码为UTF-8，否则在输入中文时可能会出现乱码或者导致未知错误

2.在输入文字时不要带有空格，否则程序会把这行输入识别为两段文字（或者多段文字，取决于你打的空格数量），然后取最后一个空格后的最后一段文字作为输出
例如：
输入“你好，世界！”
实际输出为：
```你好，世界！```
输入“你好 世界！”
实际输出为：
```世界！```

#有其他问题或者建议？
请直接在项目中提issue，作为一位在校大学新牲我会及时查看并协助你解决问题，或者采纳建议（
