# HelloFace
教师管理系统 <br/>
项目网址：http://118.25.45.160/HelloFace<br/>

教师可以在线申请账号，申请的账号需要等待后台管理员“激活”才具有“登入”的资格<br/>
教师功能：<br/>
  	 根据修改 “个人账号信息”<br/>
  	 查询与自己关联的学院、专业的班级学生签到信息<br/>
管理员功能：<br/>
  	 根据学院，找到学院下的专业，从而找到专业下面的班级（下拉框利用 Ajax实现二级联动）<br/>
	  根据学生的姓名关键字、学号的id进行模糊查询<br/>
	  将学生的信息放到 LayUI表单中，采用 LayUI的分页查询方式<br/>
	  可以增加、删除、修改学生的信息<br/>
	  管理教师申请的列表，实现教师申请账号的激活，激活的账号才可以登入后台<br/>

前端采用LayUI框架：https://www.layui.com/<br/>
后端采用 :Spring + Spring MVC + MyBatis<br/>
数据库采用：MySql<br/>
项目管理工具: Maven<br/>
servlet 容器采用：tomcat 7.0<br/>

MyBatis 用到的 pojo 类和 mapper接口及mapper映射文件 采用“逆向工程”生成，涉及到关联查询自己手写<br/>
