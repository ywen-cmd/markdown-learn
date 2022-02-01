# <span id="top">Markdown语法</span>



---
[TOC]
---



## 标题

# hello world

## hello world

###### hello world

<h1>hello world</h1>

ctrl + / 用于显示markdown文本的源代码格式



## <span id="wb">文本</span>

*使用ctrl + 数字键 1-6 可以得到 1-6的标题，之后我们会通过主题给这些格式加上颜色，现在还没有*

##### 斜体 

*hello* _tttt_ <em>你好世界</em>

##### 粗体

**hello**

##### 删除线

~~hello world~~

##### 下划线

<u>hello world</u>

##### 标记的组合使用

<u>*nihao*</u>

##### 列表

###### 有序列表

1. 北京
   1. 海淀
   2. 朝阳
      1. 望京
      2. 来广营
2. 上海
3. 广州

###### 无序列表

- 北京
  - 海淀
  - 朝阳
    1. 望京
    1. 来广营
- 上海
- 广州



##### 超链接

[百度](www.baidu.com)

##### 引用

> ​					长歌行
>
> >​									李白
> >
> >adasjdakjdakjljakfjksafkljsf
> >sdfjsdafsdjkafsdjlakfsjkldfjs
> 
>我可以任意改变左边的嵌套级别



##### 横线

---

<hr/>



## 图片

##### 网络

![bilibili](https://gimg2.baidu.com/image_search/src=http%3A%2F%2Finews.gtimg.com%2Fnewsapp_match%2F0%2F11909995508%2F0.jpg&refer=http%3A%2F%2Finews.gtimg.com&app=2002&size=f9999,10000&q=a80&n=0&g=0n&fmt=jpeg?sec=1646144345&t=b51392d52751b42d12f1a057b528b93b)

##### 本地

![local mac pic](C:\Users\文源\Pictures\Camera Roll\macos10.13秋天风景4K壁纸_彼岸图网.jpg)



## 表格

##### 基本样式

| 你好 | 阿松大 |      |
| :--: | :----: | ---- |
| 哈哈 |   xs   |      |

<u>***使用typora的段落->表格->插入就可以了，还可以调整居中之类的格式***</u>



##### 扩展样式

使用`html`插入复杂样式，网站：https://www.tablesgenerator.com/html_tables

<table>
<thead>
  <tr>
    <th>1</th>
    <th>2</th>
    <th>3</th>
    <th>4</th>
    <th>5</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>2</td>
    <td>1</td>
    <td>1</td>
    <td>1</td>
    <td>1</td>
  </tr>
  <tr>
    <td>1</td>
    <td>1</td>
    <td colspan="2" rowspan="2">6</td>
    <td>1</td>
  </tr>
  <tr>
    <td>1</td>
    <td>1</td>
    <td>1</td>
  </tr>
  <tr>
    <td>2</td>
    <td>3</td>
    <td>4</td>
    <td>4</td>
    <td>4</td>
  </tr>
</tbody>
</table>








## 代码

##### 行内代码

`cout << "hello world!" << endl;"`



##### 块级代码

```cpp
#include<iostream>
using namespace std;
@test
int main(){
    cout << "hello world" << endl;
    return 0;
}
```



## 任务清单

任务统计表

- [ ] 星期一
- [ ] 星期二
- [ ] 星期三
- [ ] 星期四
- [ ] 星期五
- [ ] 星期六
- [x] 星期日



## Emoji

😊😁🤣🍟🎈🚕🚗

:smile:

:fire:

在*win10*系统中使用`win + .`就可以调出来



## 视频

<video src="https://www.bilibili.com/video/BV1nh411r7rW?p=3"/>

##### 本地视频

<video src="D:\迅雷下载\bilibili-doc-master\Markdown从小白到精通\乌鸦哥.mp4" />

##### b站视频

<iframe src="//player.bilibili.com/player.html?aid=543279069&bvid=BV1Fi4y1w71m&cid=271094288&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>



## 主题

主题使用github_myself.css自定义主题

视频链接：https://www.bilibili.com/video/BV1nh411r7rW?p=6



## **页面跳转**

<a href='#wb'>回到文本</a>

[回到图片](#图片)

<a href='#top'>go to top</a>

