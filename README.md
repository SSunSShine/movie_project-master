# movie_project-master
movie_project-master Web APP
文件夹               内容
admin               后台页面
home                主页面
static              前端静态页面的模板以及一些图片视频等
templates           前端文件
config              配置
py文件
__init__.py         初始化python文件
generate_tables.py  在MySql moive数据库里建表
manage.py           运行manage脚本服务器



基础运行环境安装:

```
cd movie_project
pipenv shell
pip install -r requirement.txt
# 新建一个movie数据库; 修改config目录下的base_config中数据库用户密码，管理员用户密码
python generate_tables.py
python manage.py runserver
```

打开网址: http://127.0.0.1:5000/ 访问首页; http://127.0.0.1:5000/admin 访问后台。
