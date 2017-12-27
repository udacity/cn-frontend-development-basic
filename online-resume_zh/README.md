# 在线简历

## 项目介绍

Udacity 第 4 个项目：[在线简历](https://github.com/udacity/frontend-nanodegree-resume)因为不可抗元素，Google 地图 API 不能用。于是就改成用高德地图的 API 了。

## 如何运行

**第 1 步(完成所需时间：10分钟左右)：** 首先在 [高德](http://lbs.amap.com/) 上注册并申请 API Key ***(是 Web 端的而不是 Web 服务，切记切记)*** ，详细申请步骤可按照下面帖子写的：
- [申请使用高德地图 api](http://discussions.youdaxue.com/t/api/37094)

**第 2 步：** 将 `index.html` 文件里的第 29 行代码的 `API_KEY` 换成你上面上一步申请到的 API Key

```html
<script src="http://webapi.amap.com/maps?v=1.3&key=API_KEY"></script>
```

**第 3 步：** 将 `resumeBuilder.js` 的添加地图代码解除注释

```javaScript
//添加高德地图到 mapDiv 上，使得简历拥有地图
$("#mapDiv").append(gaodeMap);
```

**最后：** have fun with it~

## 项目指南

如何做这个项目，看下面的指导
- [项目详细的指导](https://classroom.udacity.com/nanodegrees/nd001/parts/0011345406/modules/296281861575462/lessons/2962818615239847/concepts/29594685550923) | 👈左边链接无法访问的点击[此处](https://classroom.udacity.com/nanodegrees/nd001-cn-basic/parts/8466cc34-4001-4ac3-a908-01729473d5e2/modules/549f914e-5a25-4174-b92e-a9c9b5931985/lessons/2962818615239847/concepts/29594685550923)

想完美通过，看下面的文档：
- [项目审阅标准](https://review.udacity.com/#!/rubrics/498/view)


## 其它

若果有办法用 Google 地图的话，就使用下面链接里的代码作为初始代码
- [在线简历](https://github.com/udacity/frontend-nanodegree-resume)

