2020年11月5日使用爬虫开发工具，搜索知乎关键词 中医 + 疫情 ，得到一些问答资料。


爬虫的原始回答*点赞数共有24万份数

数据进行了清洗。
点赞数默认为零的直接放弃了

英文转换 如 COVID CoVID Covid 统一转换成 COVID


具体的代码到时候会传入网上...

表格数据：https://www.wjx.cn/mobile/statnew.aspx?activity=95912339&reportid= 请访问上面的链接查看结果，密码为:jay12345678

感谢，枫知淇大佬爬虫工具基于枫知淇大佬的，我做了稍稍的修改。回答多的话(100条以上)一般是取：以点赞数从高到低排序，前2%的；回答数少(100条以下)基本上搜索到所有的回答。

点赞数写到了文件名字后缀上...

爬虫修改参数 :中医 +疫情 的使用参数 management.py 里面修改参数 offset total

他的github开发爬虫:https://github.com/Milloyy/ZhihuSpider


MIT License

Copyright (c) 2020 枫知淇

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.