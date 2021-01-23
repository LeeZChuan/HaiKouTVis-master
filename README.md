# HaiKouTVis(海口市交通流量可视化系统)

项目演示网页：https://leezchuan.github.io/HaiKouTVis-master/

 CCF海口市-交通流量时空演变特征可视分析 第三名作品 
 含项目工程源码、答卷

 ## 技术栈
     ECharts + Tableau + HighCharts.js + Python

`````
1. data文件夹包含系统所需数据集文件：
   -data   
       -Y-M-D_start/dest：     热力图数据
       -fastcar：              实时统计视图数据
       -increament：           变化率视图数据
       -kedoutu：              蝌蚪图数据
       -qianxitu：             迁徙图数据
       -yuce：                 9个预测点订单预测数据
       -Y-M-D_hexiantu.json：  和弦图数据
       -Y-M-D_lineChart.json： 出行距离与订单数量视图数据
       -calendarHeatMap.json： 日历热力图数据       
       -prediction.json：      整体订单预测数据

2. 运行index.html;

3. 由于数据量过大，仅上传其中具有代表性的几天数据，进行系统测试：
   2017-05-13、2017-05-14、2017-05-15、2017-05-16、2017-05-17、
   2017-09-30、
   2017-10-01
`````



## 代码结构
```
HaiKouTVis
│
├── css  # 网页样式
│ 
├── data # 作图数据存放
│ 
├── js：#项目所需库文件，以及作图所需本地文件
│ 
├── pdf：#这里是我们比赛提交的答卷：
│
├── index.html：#项目页面
│
└── README.md # 此说明文件
```

## 答卷&论文

在pdf文件中


## 其他

* 感兴趣的可以关注我的个人公众号，上面会不时分享相关技术与心得

* 公众号名称：当生活遇上Coding

![公众号](images/微信公众号.jpg)

Copyright (c) 2020-present LeeZChuan
