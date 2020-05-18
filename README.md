# QualityControl
1.网络设备和服务器品质监控，包括ping，路由，cpu等各种参数
2.可以修改QualityControl/public_static/custom_js/echart_china_map.js中的geoCoord参数来指定全国各地地点，然后对应的json格式文件也要修改，就能展示任意两点的的ping监控了，单位是ms
3.目前展示的三个地方循环图形，北京15个，上海2个，广东15个，这个可以通过修改echart_china_map.js文件的js部分进行自定义数量的图形循环
4.此项目为django项目，因为没有用到数据库信息，所以选用的sqlite数据库
5.进入项目目录，执行python3 manage.py runserver 0.0.0.0:8001，即可前台运行，访问对应ip加端口既可看到图形，端口可以自定义
