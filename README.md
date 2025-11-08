# 前言

速达物流信息查询微信小程序是基于SSM框架，结合Vue、Uniapp等前端技术，为用户提供便捷的物流信息查询服务。本项目致力于解决物流信息查询不便的问题，通过微信小程序的形式，让用户能够随时随地进行查询。

# 内容介绍

本项目主要包括以下功能模块：

1. 用户模块：提供用户注册、登录、修改个人信息等功能。
2. 物流查询模块：支持用户输入运单号，查询物流信息。
3. 历史记录模块：记录用户查询过的物流信息，方便用户随时查看。
4. 物流公司模块：展示支持的物流公司列表，供用户选择。

# 技术介绍

- 语言：Java
- 使用框架：Spring、Spring MVC、MyBatis、微信小程序
- 前端技术：JS、Vue、CSS3、Uniapp
- 开发工具：IDEA/Eclipse、Uniapp
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpStudy/Navicat
- JDK版本：JDK 1.8
- Maven：Apache Maven 3.8.1-bin
- 前端环境：Node.js 12/14/16

# 核心代码

以下是一段查询物流信息的核心代码：

```java
// 物流信息查询接口
@RequestMapping("/queryLogistics")
@ResponseBody
public Result queryLogistics(@RequestParam("waybillNo") String waybillNo) {
    try {
        Logistics logistics = logisticsService.queryByWaybillNo(waybillNo);
        if (logistics != null) {
            return new Result(true, "查询成功", logistics);
        } else {
            return new Result(false, "查询失败，请检查运单号是否正确");
        }
    } catch (Exception e) {
        e.printStackTrace();
        return new Result(false, "服务器异常，请稍后再试");
    }
}
```

# 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图
![封面图片](https://img10.360buyimg.com/ddimg/jfs/t1/330346/3/12823/283114/68c59956F0d7b60a4/c14433521722f26c.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/334996/9/12935/28938/68c5992eFec32a16a/6ab881024227c9e2.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/330920/28/13083/28251/68c5992eF7f2a6b3f/37fce0e77796a4eb.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/345676/4/3138/18091/68c5992eF6228d470/7ab7364439a1da01.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/340758/23/10403/48198/68c5992eFd2aee3be/01744565a30a67ef.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/338813/11/10324/85665/68c5992fFcd51eeaa/8a02a5f871082fdc.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/337249/15/10364/52368/68c5992fF91f0cf5f/24c37eaf983862a3.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/347974/7/3161/26573/68c5992fF1bd40c81/f3bff7a449645e57.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/325371/11/19550/9406/68c5992fFaed6a573/afb5838e91e85666.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/332126/27/12960/73557/68c59930F91a87f55/69b2a7d04bebbae9.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
