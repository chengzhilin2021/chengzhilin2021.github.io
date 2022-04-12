## Welcome to GitHub Pages

想看看我的项目吗？
===
* 1.**Python-Requests** 
* [Gitee项目](https://gitee.com/chengzhilin2021/Python-Requests)
* [Github项目](https://github.com/chengzhilin2021/Python-Requests/)

这里附上一段代码
===

### 注：使用语言是Python

```
url = input(r"请输入您要查看的网址:") #询问查看的网址
print(r"如果爬取失败，与本软件和作者无关！") #免责声明
print(r"请输入是否添加http：//或https：//")
Return = input(r"如果已添加，请输入Y，否则请输入N(注意大小写):")
if Return == "Y" :
    print("准备爬取")
    response = requests.get(url,headers=header) #将爬取的值保存至变量
    response.encoding='utf-8' #将其转化为utf-8格式
    html=response.text #将返回值转化为源码
    print(html) #打印源码
    #打印空行
    print()
    print()
    print()
    print()

    #结束
    print("爬取完成")
    input("按任意键退出")
    exit()
```

我的Bilibili主页
===
* [传送门](https://space.bilibili.com/1622070848)

