# 前言

随着新冠疫情的全球肆虐，校园作为人群密集的场所，防控工作尤为重要。为此，我们开发了一套校园疫情防控系统，旨在帮助校园实现疫情的有效监控与管理。本项目使用Java语言，结合Spring Boot框架，前端技术JS、Vue和CSS3，以及MySQL数据库，为校园疫情防控提供全方位的技术支持。

# 内容介绍

本项目主要包括以下功能模块：用户管理、疫情信息发布、健康打卡、行程上报、数据分析等。用户管理模块实现对师生信息的统一管理；疫情信息发布模块用于及时发布校园疫情防控通知；健康打卡模块方便师生上报体温及健康状况；行程上报模块用于记录师生的出行信息；数据分析模块为校园疫情防控提供数据支持。

# 技术介绍

- 语言：Java
- 使用框架：Spring Boot
- 前端技术：JS、Vue、CSS3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven：apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

# 核心代码

以下为项目中的部分核心代码：

```java
// 健康打卡接口
@PostMapping("/checkIn")
public ResponseEntity<?> checkIn(@RequestBody CheckInRequest request) {
    // 校验参数
    if (request.getTemperature() == null || request.getHealthStatus() == null) {
        return new ResponseEntity<>(HttpStatus.BAD_REQUEST);
    }

    // 保存健康打卡信息
    checkInService.saveCheckIn(request.getUserId(), request.getTemperature(), request.getHealthStatus());

    return new ResponseEntity<>(HttpStatus.OK);
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

![封面图片](https://img10.360buyimg.com/ddimg/jfs/t1/286509/26/19407/176597/689ef09cF43f455d9/013a43442d075be1.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/312839/31/26723/117050/689ef078F0ebc3389/5ad68595b0a6f9a6.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/312666/20/26781/79423/689ef079F295d7586/8d6638acf91380c9.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/292959/21/22637/21369/689ef079F57f4a0d8/1b861d70ad39bee3.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/311582/18/26906/81089/689ef079Fbd654dc3/bd2288e6450fb104.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/310483/6/26875/33155/689ef07aF50a0c520/a9e8bdd3bfe0d9ae.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/312043/3/26635/36582/689ef07bF41247500/dd0bf864f2edb7b4.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/314424/36/26771/35672/689ef07bFbe790fda/8ac406ce4df05667.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/325215/3/4918/41535/689ef07cF3a1f895d/ecd1b5b0548b78c2.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/325459/33/4927/47388/689ef07cF60d359d6/fb89d77ebc6bddd8.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
