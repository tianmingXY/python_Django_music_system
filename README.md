# python_Django_music_system
基于python语言的Django框架的大数据音乐推荐系统，项目自带爬虫，数据库MySQL，带论文文档

# B站演示视频地址   https://www.bilibili.com/video/BV1Qm411d7RD/?spm_id_from=333.999.0.0

基于Django的音乐个性化推荐系统 
技术栈：python的Django框架  +   MySQL数据库 + vue框架
推荐算法：协同过滤算法 
技术人员扣扣： 1516993194

系统访问网址
http://localhost:8080/

项目部署步骤：
1. python manage.py makemigrations //数据迁移
2. python manage.py migrate
3. python manage.py runserver 127.0.0.1:8080 //启动服务

后台管理员账号密码设置生成
python manage.py createsuperuser --username=admin --email=admin@163.com


【换后台管理员界面UI】
https://blog.csdn.net/m0_54219225/article/details/127809007

[Django]在数据库有表，但是没有model的情况下对数据查询，修改
https://blog.csdn.net/qq_37099834/article/details/82754170


pip配置阿里镜像
pip config set global.index-url https://mirrors.aliyun.com/pypi/simple/
pip config set install.trusted-host mirrors.aliyun.com
