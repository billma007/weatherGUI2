# weatherGUI2

A python project that can search for weather in People's Republic of China(INCLUDING TAIWAN PROVINCE)

## What's this?/项目简介

Creating a GUI window through PyQt5 can query the weather conditions and clothing recommendations of all cities in the People's Republic of China (**including Hong Kong, Macao and Taiwan**).

通过PyQt5创建GUI窗口并引用中国天气网的API能查询中华人民共和国（**包括港澳台**）的所有城市天气情况以及着装建议。

## How to use it?/如何使用

```cmd
git clone https://github.com/billma007/weatherGUI2.git
cd weatherGUI2
pip install -r requirements.txt
python3 weather.py
```

## Environment/环境

- Python3.7+
- Git

## Architecture/架构

- [Weather.py](Weather.py)------主程序/Main
- [Ui_weather.py](Ui_weather.py) -------GUI界面的搭建/GUI CREATION
- [query.py](query.py)------数据分析与处理/Data Analyse
- [requirements.txt](requirements.txt)------第三方pip库支持/Requirements
- [LICENSE](LICENSE)------MIT LICENSE
- [city_code.txt](city_code.txt)------utf-8字符转换成受支持的API接口字符，在2.0.0Developer Beta后可自行生成/Change UTF-8 into supported code
- [README.md](README.md)------README

## 更新日志/Update log

- 2022/3/8 2.0.1版本出炉，可以自动生成`city_code.txt`文件，解决了目录下没有该文件导致报错的问题。
- 2022/3/7 2.0.0正式版发布，正式使用PyQt5生成**GUI**界面，操作更加便捷
- 2022/3/6 1.3.0发布，修复了API接口报错的问题
- 2022/3/5 1.2.1-2版本增加了utf-8字符的兼容性，可以不用拼音代替中文字符。同时2.0.0GUI版开始制作
- 2022/3/4 1.1版本，修复了大量bug
- 2022/3/3 1.0发布，支持拼音查询天气
- 2022/3/2 打表完毕(~真他妈累~真开心)
- 2022/3/1 开始制作

## 关于作者/About

江苏省苏州市的一个普通高中牲，一个~因为玩电脑被学校处分~在省赛就被刷下来的信息学奥林匹克竞赛选手，热爱编程，但不喜欢前端。

欢迎通过以下联系方式与我探讨信息竞赛、博客搭建、学术讨论以及扯皮：

- QQ:36937975
- Twitter:@billma6688
- Facebook/Instagram:billma007
- CodeForces/USACO/AtCoder:billma007(不常用/not use them usually)
- Email:maboning237103015@163.com

## 推广：个人博客/Blog

[欢迎来到我的博客/Welcome Here!](https://billma.top)

## LICENSE

[MIT LICENSE](LICENSE)
