# 流浪动物救助系统-宠物驿站

![登陆界面](https://wx-ma1.oss-cn-beijing.aliyuncs.com/animal.jpg "登陆界面.png")

####  **联系作者** 

![联系作者](https://wx-ma1.oss-cn-beijing.aliyuncs.com/main-platform.png "联系作者.png")

 **这是作者的微信二维码，如需本项目源代码，可扫码联系联系作者。**  
  

![微信二维码-1](https://wx-ma1.oss-cn-beijing.aliyuncs.com/wx.jpg?x-oss-process=image/resize,p_50 "微信二维码-1.png")

![登陆界面](https://wx-ma1.oss-cn-beijing.aliyuncs.com/animal.jpg "登陆界面.png")



**系统功能持续更新中。。。**
#### 介绍
**
  本系统分为后台管理系统端和微信小程序端。是基于SSM框架的流浪猫狗领养救助平台管理系统，平台用户可以在浏览器登录系统后进行一系列操作。
同时系统具备微信小程序端，用户也可以在微信小程序端进行一系列的操作。本系统使用了SpringBoot2.X VUE2.6 Antd1.7.2  MyBatisPlus Shiro1.5.0 Java1.8等一系列技术。** 

** 后台管理系统具备的功能：
1.实现了系统管理，包括了，系统用户管理，权限管理，角色管理
2.实现宠物救助站的账务记录，宠物领养申请，小程序轮播图，小程序用户信息功能。
3.实现了宠物养殖攻略发布功能，待领养宠物查看功能，浏览消息功能，救助站列表功能等。** 

** 小程序端具备的功能：
1，实现了小程序登录注册，首页轮播图，宠物信息查看功能
2，实现了宠物发布功能，送养信息，寻主信息功能，查看公告信息功能，发布和查看留言等功能
3，实现了救助站信息查看功能，足迹查看功能，领养申请查看功能。
** 
#### 项目所用技术
|技术点   | 描述  | 备注   |
| :------------: | :------------: | :------------: |
|  SpringBoot2.X | 先进的Spring集成框架  | 集成了最新版  |
| VUE2.6  |  前端交互框架 |   |
| ElementUI 2.x |  饿了么出品的前端UI框架 |   |
| ANTD |  阿里出品的图表框架  | 好用且好看  |
| MyBatisPlus | 基于MyBatis封装的ORM框架  |方便查询   |
| Shiro1.5.0 | 经典而好用的权限框架  |  |
| uniapp | 移动端开发框架  |  |
| uview | 高颜值的移动端UI框架  |  |
| Java1.8 | 最常用的Java版本  |使用了Java8新特性  |
| RBAC权限模型|纯动态的菜单权限设计，可控制权限到按钮级别  |纯动态的菜单权限设计  |
#### 清晰的注释
**项目的每个类和方法，都具备清晰的注释，适合阅读，注释如下图：**

**1. 类注释**

![类注释](https://www.skywalking.pro/download/images/meta/WX20230206-092916@2x.png "类注释")

**2. 数据库字段注释注释**

![类注释](https://www.skywalking.pro/download/images/meta/WX20230206-093511@2x.png "类注释")
#### 项目特有优势
1. 清晰的注释，每个方法，类，字段，都具备中文注释。
2. 部署方便，作者编写了一键启动的脚本，可以让Java后端完美运行在主流服务器上。
3. 代码符合行业规范，变量，类，命名简洁优雅。
4. 应用多种市面上的先进技术，方便学习和开发。
5. 具备完整的项目文档和技术文档，方便二次开发。
6. 具备前后端代码生成器，一键生成VUE以及Java后端代码。 
#### 它适合做什么？
1. 适合作为高校毕业设计。
2. 适合作为初学者学习使用。
3. 如果场景适合，可以作为商业使用。
### 联系作者
#### 微信号: SkyLearningPro
#### 系统演示地址:
```
登录地址: https://www.skywalking.pro/animal-platform
登录账号: admin
登录密码: 123456
```
#### 小程序二维码:

![小程序二维码](https://www.skywalking.pro/download/images/animal-platform/gh_696e0775de4b_258.jpg "小程序二维码.png")

**若演示程序不可用，可翻到文末扫码联系作者微信或者留言**

### 软件架构说明
该项目采用市面上比较流程的前后端分离架构，以SpringBoot技术栈为后端，以VUE为前端，采用优雅简洁漂亮的UI框架。系统采用前端发起请求，后端处理业务的方式进行交互，相对于传统的JSP，freemarker等技术有较大区别以及先进性。同时在权限控制方面有独到的创新，实现了VUE自定义指令，以控制系统权限到每一个系统按钮。是非常适合作为毕业设计以及学习的系统。
#### 前端技术
1. ElementUI
2. 页面,按钮级别权限控制。
3. 多个组件封装，调用方便。
4. Antv图表组件。
5. WebPack
6. ES6
7. 多环境打包。
8. VUE路由，过滤器，自定义指令。
9. 代码简洁，符合编码规范。
#### 后端技术
1. SpringBoot2.x
2. Shiro权限框架
3. Redis6.X最新版
4. MyBatis注解版
5. MySQL6.7
6. 分模块开发，自定义启动脚本，JVM调优
7. 多环境,前后端完全分离。
8. 代码生成器。
9. orika传输对象映射器。

### 系统技术文档
**为了让读者更好地理解系统技术原理，功能实现方法，故特地准备了系统技术文档，里面包含系统所使用的主要技术框架，运行说明，系统表设计，模块设计等。**
#### 系统技术文档截图

![系统技术文档截图](https://www.skywalking.pro/download/images/animal-platform/WX20220812-094722@2x.png "系统技术文档截图.png")

### 项目代码展示

#### 管理系统VUE代码截图展示

![前端VUE代码截图展示](https://www.skywalking.pro/download/images/animal-platform/WX20220812-094850@2x.png "管理系统VUE代码截图展示.png")

#### 小程序前端代码截图展示

![小程序前端代码截图展示](https://www.skywalking.pro/download/images/animal-platform/WX20220812-095003@2x.png "小程序前端代码截图展示.png")

#### 管理系统后端Java代码截图展示

![管理系统后端Java代码截图展示](https://www.skywalking.pro/download/images/animal-platform/WX20220812-095251@2x.png "管理系统后端Java代码截图展示.png")

#### 小程序后端Java代码截图展示

![小程序后端Java代码截图展示](https://www.skywalking.pro/download/images/animal-platform/WX20220812-095507@2x.png "小程序后端Java代码截图展示.png")

#### 数据库表结构展示

![数据库表结构展示](https://www.skywalking.pro/download/images/animal-platform/WX20220812-095552@2x.png "数据库表结构展示.png")

### 系统截图展示
#### 系统登陆
- 登陆界面

![登陆界面](https://wx-ma1.oss-cn-beijing.aliyuncs.com/animal.jpg "登陆界面.png")

#### 系统管理模块
- 系统主页

![主页](https://www.skywalking.pro/download/images/animal-platform/WX20220812-094328@2x.png "主页.png")

- 菜单管理

![菜单管理](https://www.skywalking.pro/download/images/animal-platform/WX20220812-100020@2x.png "菜单管理.png")

![菜单编辑](https://www.skywalking.pro/download/images/animal-platform/WX20220812-100106@2x.png "菜单编辑.png")

- 角色管理

![角色管理](https://www.skywalking.pro/download/images/animal-platform/WX20220812-100146@2x.png "角色管理.png")

![角色编辑](https://www.skywalking.pro/download/images/animal-platform/WX20220812-100243@2x.png "角色编辑.png")

- 系统用户管理

![系统用户列表](https://www.skywalking.pro/download/images/animal-platform/WX20220812-100347@2x.png "系统用户列表.png")

![系统用户编辑](https://www.skywalking.pro/download/images/animal-platform/WX20220812-100347@2x.png "系统用户编辑.png")

#### 系统监控模块

- 系统日志

![系统日志](https://www.skywalking.pro/download/images/animal-platform/WX20220812-100545@2x.png "系统日志.png")

#### 业务模块

- 账务记录管理模块

![账务记录管理模块](https://www.skywalking.pro/download/images/animal-platform/WX20220812-100654@2x.png "账务记录管理模块.png")

- 领养申请列表模块

![申请列表](https://www.skywalking.pro/download/images/animal-platform/WX20220812-100755@2x.png "申请列表.png")

- 小程序轮播图模块

![小程序轮播图模块](https://www.skywalking.pro/download/images/animal-platform/WX20220812-100906@2x.png "小程序轮播图模块.png")

- APP（小程序）用户信息

![输入图片说明](https://www.skywalking.pro/download/images/animal-platform/WX20220812-100956@2x.png "APP用户信息.png")

- 养宠攻略模块

![养宠攻略列表](https://www.skywalking.pro/download/images/animal-platform/WX20220812-101113@2x.png "养宠攻略列表.png")

![编辑养宠攻略](https://www.skywalking.pro/download/images/animal-platform/WX20220812-101224@2x.png "编辑养宠攻略.png")

- 待领养宠物模块

![待领养宠物信息列表](https://www.skywalking.pro/download/images/animal-platform/WX20220812-101320@2x.png "待领养宠物信息列表.png")

![新增待领养宠物](https://www.skywalking.pro/download/images/animal-platform/WX20220812-101411@2x.png "新增待领养宠物.png")

![待领养宠物编辑](https://www.skywalking.pro/download/images/animal-platform/WX20220812-101458@2x.png "待领养宠物编辑.png")

- 留言消息

![留言消息列表](https://www.skywalking.pro/download/images/animal-platform/WX20220812-101613@2x.png "留言消息列表.png")

- 救助站信息模块

![救助站信息列表](https://www.skywalking.pro/download/images/animal-platform/WX20220812-101705@2x.png "救助站信息列表.png")

![救助站信息列表新增](https://www.skywalking.pro/download/images/animal-platform/WX20220812-101802@2x.png "救助站信息列表新增.png")

![救助站信息列表编辑](https://www.skywalking.pro/download/images/animal-platform/WX20220812-101904@2x.png "救助站信息列表编辑.png")


#### 后台系统功能模块概要
+ 系统登陆
+ 系统主页
  - 系统主页折线图统计
    * 系统主页折线图统计
    + 系统模块导航
    - 系统在线数，访问数统计
+ 系统管理
  - 系统用户管理
    * 系统用户条件查询
    + 系统用户修改
    - 系统用户删除
	- 系统用户新增
  - 系统菜单管理
    * 系统菜单条件查询
    + 系统菜单修改(可级联修改)
    - 系统菜单删除
	- 系统菜单新增
  - 系统角色管理
    * 系统角色条件查询
    + 系统角色修改
    - 系统角色删除
	- 系统角色新增
  - 系统字典管理
    * 系统字典条件查询
    + 系统字典修改
    - 系统字典删除
	- 系统字典新增
+ 系统监控
  - 在线用户管理
    * 在线用户条件查询
    + 在线用户踢出
  - 系统日志管理
    * 系统日志条件查询
    + 系统日志分析
	+ 系统访问IP分析
  - 系统请求追踪
    * 请求耗时追踪
    + 请求方法追踪
	+ 请求URL追踪
	+ 请响应状态追踪
  - 系统信息
    * JVM信息监控
    + 服务器信息监控
	+ 请求URL追踪
	+ 请响应状态追踪
+ 账务记录管理
  - 账务记录管理
    * 账务记录条件查询
    + 账务记录新增
	* 账务记录修改
    + 账务记录批量删除
+ 领养申请管理
  - 领养申请列表
    * 领养申请条件查询
    + 领养申请新增
	* 领养申请修改
    + 领养申请批量删除
+ APP轮播图管理
  - APP轮播图列表
    * APP轮播图条件查询
    + APP轮播图新增
	* APP轮播图修改
    + APP轮播图批量删除
+ APP用户模块
  - APP用户列表
    * APP用户条件查询
    + APP用户新增
	* APP用户修改
    + APP用户批量删除
+ 养宠攻略模块
  - 养宠攻略列表
    * 养宠攻略条件查询
    + 养宠攻略新增
	* 养宠攻略修改
    + 养宠攻略批量删除
+ 留言消息模块
  - 留言消息列表
    * 留言消息条件查询统计
    + 留言消息新增
	* 留言消息修改
    + 留言消息批量删除
+ 救助站信息信息模块
  - 救助站信息列表
    * 救助站条件查询
    + 救助站新增
	* 救助站修改
    + 救助站批量删除
	+ 救助站分配



#### 演示地址
```
登录地址: https://www.skywalking.pro/animal-platform
登录账号: admin
登录密码: 123456
```
若演示地址不可用，可扫码联系作者微信或者留言

####  **联系作者** 

 **这是作者的微信二维码，如需本项目源代码，可扫码联系联系作者。**  
 

![微信二维码-1](https://wx-ma1.oss-cn-beijing.aliyuncs.com/wx.jpg?x-oss-process=image/resize,p_50 "微信二维码-1.png")

#### 安装教程

#### 后端安装方法

```
1.  mvn clean package
2.  tar -zxvf animal-platform-api.tar.gz (解压tar包)
3.  cd animal-platform-api
5.  sh /sbin/startup.sh dev
```
#### 前端安装方法

```
1.  yarn install (安装node_moudle)
2.  yarn start (启动)
3.  yarn build:pro (构建生产包)
```
