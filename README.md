**项目说明** 
- renren-security-boot是基于[renren-security](http://git.oschina.net/babaio/renren-security)，用Spring Boot实现的J2EE快速开发平台
- 使用renren-security-boot搭建项目，只需编写30%左右代码，其余的代码交给系统自动生成
- 一个月的工作量，一周就能完成，剩余的时间可以陪家人、朋友、撩妹、钓凯子等，从此踏入高富帅、白富美行业
- 也是接私活的利器，能快速完成项目并交付，轻松赚取外快，实现财务自由，走向人生巅峰（接私活赚了钱，可以给作者打赏点辛苦费，让作者更有动力持续优化、完善）
 


**具有如下特点** 
- 友好的代码结构及注释，便于阅读及二次开发
- 实现前后端完全分离，前端再也不用关注后端技术
- 灵活的权限控制，可控制到页面或按钮，满足绝大部分的权限需求
- 页面交互使用Vue2.x，极大的提高了开发效率
- 完善的代码生成机制，可在线生成entity、xml、dao、service、html、js、sql代码，减少70%以上的开发任务
- 引入quartz定时任务，可动态完成任务的添加、修改、删除、暂停、恢复及日志查看等功能
- 引入API模板，根据token作为登录令牌，极大的方便了APP接口开发
- 引入Hibernate Validator校验框架，轻松实现后端校验
- 引入云存储服务，已支持：七牛云、阿里云、腾讯云等
- 引入swagger文档支持，方便编写API接口文档
- 引入路由机制，刷新页面会停留在当前页


**如何交流、反馈、参与贡献？** 
- 项目主页：http://www.renren.io/open/
- 开发文档：http://www.renren.io/open/doc.html
- oschina仓库：http://git.oschina.net/babaio/renren-security-boot
- github仓库：https://github.com/sunlightcs/renren-security-boot
- [编程入门教程](http://www.renren.io)：http://www.renren.io   
- 官方QQ群：324780204、145799952
- 如需关注项目最新动态，请Watch、Star项目，同时也是对项目最好的支持
- 技术讨论、二次开发等咨询、问题和建议，请移步到QQ群324780204、145799952，我会在第一时间进行解答和回复！


**API文档：**
![输入图片说明](http://cdn.renren.io/img/9e7c5135b1154268ab5066d3a09fe7e1 "在这里输入图片标题")

**Layui主题风格：**
![输入图片说明](http://cdn.renren.io/img/2f6a43b9081e421ab8aa596155cd0ffc "在这里输入图片标题")

**AdminLTE主题风格：**
![输入图片说明](http://cdn.renren.io/img/44907148dd254064922a80cfddcc9b53 "在这里输入图片标题")
![输入图片说明](http://cdn.renren.io/img/f38a062145b141bf81157b495277d224 "在这里输入图片标题")
![输入图片说明](http://cdn.renren.io/img/65d7fb1906934e56abf8b8ca7e1c4541 "在这里输入图片标题")
![输入图片说明](http://cdn.renren.io/img/de740e471280429cb888f521e02ee787 "在这里输入图片标题")
![输入图片说明](http://cdn.renren.io/img/a8bc68f69288424697682f170ee40744 "在这里输入图片标题")
![输入图片说明](http://cdn.renren.io/img/92cd56f397754292a1a182f662a7e883 "在这里输入图片标题")
![输入图片说明](http://cdn.renren.io/img/0b56efe56fd64ed18e33a9e6dbb6e88c "在这里输入图片标题")







 **技术选型：** 
- 核心框架：Spring Boot 1.5
- 安全框架：Apache Shiro 1.3
- 视图框架：Spring MVC 4.3
- 持久层框架：MyBatis 3.3
- 定时器：Quartz 2.3
- 数据库连接池：Druid 1.0
- 日志管理：SLF4J 1.7、Log4j
- 页面交互：Vue2.x


 **软件需求** 
- JDK1.8+
- MySQL5.5+
- Tomcat7.0+
- Maven3.0+



 **本地部署**
- 通过git下载源码
- 创建数据库renren-security-boot，数据库编码为UTF-8
- 执行doc/db.sql文件，初始化数据
- 修改application.properties文件，更新MySQL账号和密码
- Eclipse、IDEA运行RenrenApplication.java，则可启动项目
- 项目访问路径：http://localhost
- API文档路径：http://localhost/swagger-ui.html
- 账号密码：admin/admin
 

**项目打赏** 

如果您觉得作者的权限系统能帮助到您，您可以打赏作者一瓶汽水
![输入图片说明](http://cdn.renren.io/img/10e0f63b327d4e7ab9113e7b9568381a "在这里输入图片标题")