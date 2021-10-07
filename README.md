# 欢迎来到我的博客！
## 引言

我是一个初入的萌新，在搭建这个小小的网页的时候，也熬过夜，一边又一遍的一边学习一边尝试。面对一个崭新的，从来没有接触过的英文界面，和从未涉足的领域，过程自然是苦涩而艰辛的，但是如果你看到了这个网页，那是我埋下的小小的梦想种子。
### 起点

> 我的全部才华都来自对我要处理的题材的热爱。只有对伟大、对真、对美的爱，才能激发我的天才。——卢梭

# 我
![这是我老婆！OWO](https://user-images.githubusercontent.com/91616087/135478131-c85f3d08-0b23-4d25-aeba-5a8e60a4c607.jpg)

# Bandit wargame
---
bandit靶场自学日记

## 1.Xshell的安装

进入Xshell的[官网](https://www.netsarang.com/en/xshell/)进行安装
![pre](https://user-images.githubusercontent.com/91616087/136350825-a052ce48-0461-44e8-8483-34a5c4bce6d0.png)
```
我选择的是personal30天使用。在选择好后在文件-会话属性-SSH-隧道中将转发X11连接到选项去勾选，如图：
```
![pre1](https://user-images.githubusercontent.com/91616087/136351219-0a5aef93-04d5-4a32-a44d-042bdfc8cd1a.png)
否则会一直提示转发到Xmanager。别问我为什么取消勾选！doge
## 1.Level 0
*Level Goal
The goal of this level is for you to log into the game using SSH. The host to which you need to connect is bandit.labs.overthewire.org, on port 2220. The username is bandit0 and the password is bandit0. Once logged in, go to the Level 1 page to find out how to beat Level 1.*<br>
lv1很简单，即连接到 `bandit.labs.overthewire.org `，并且使用 `bandit0 `作为账户和密码登录。<br>
我使用的是新建会话的方式，如下图分别填好SSH，port，账户和密码；
![bandit0 1](https://user-images.githubusercontent.com/91616087/136353769-6be31b48-aff4-4bba-829b-72dd79f50013.png)，![bandit0 2](https://user-images.githubusercontent.com/91616087/136353810-ecc992a6-6253-42b3-8dd9-410e73e0d74a.png)<br>
或者输入 `ssh bandit0@bandit.labs.overthewire.org -p 2220 `连接后输入提示的password。
## 2.Level 0-1
lv1是对游戏的再一次简介，帮助再次了解这个游戏。从Lv1正式开始。（然后我对着这个全英文翻译了半天，发现什么用都没有，我也是服了= =！）<br>
*Level Goal
The password for the next level is stored in a file called readme located in the home directory. Use this password to log into bandit1 using SSH. Whenever you find a password for a level, use SSH (on port 2220) to log into that level and continue the game.*<br>
本关的flag藏在**readme**下，需要我们进行读取。
![bandit1 1](https://user-images.githubusercontent.com/91616087/136355480-2956fcd4-8b10-43e0-b68e-e3c0a8f66fd0.png)
```
直接用ls指令查看当下的文件，或者使用ls-a指令。发下下属readme文件。用cat指令进行读取。得到flag
```
`boJ9jbbUNNfktd78OOpsqOltutMc3MY1`






[SSH](ssh为secureshell的缩写。 "什么是ssh")也给我造成了巨大的麻烦。
### 加藤惠照片
<![Kato_Megumi1](https://user-images.githubusercontent.com/91616087/135485196-d49f1572-8327-4d18-a65f-8db17d224ab6.gif),![Kato_Megumi3](https://user-images.githubusercontent.com/91616087/135485474-981816bf-19e9-4bae-8d78-c67af71f0be1.gif)>

​
### 假期安排
​
明日假期自己安排！
​
| 项目 | 时长 |     内容 |
| :----- | :--: | -------: |
| 高数 |  1h  | 理解极限思想 |
| C语言 |  1h | 自学 |
| 英语 |  0.5h  | 完成演讲稿的写作 |
### 自学来源
[百度](https://www.baidu.com) `https://www.baidu.com`<br>
[CSDN——专业开发者社区](https://www.csdn.net/) `https://www.csdn.net/`<br>
[知乎](https://www.zhihu.com/) `https://www.zhihu.com/`
### 致谢
---
* 
