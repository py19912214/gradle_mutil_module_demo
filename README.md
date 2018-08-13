# gradle_mutil_module_demo
gradle 多模块demo
main模块为空膜拜 并且 引用subweb跟subinter模块 
subweb中有一个页面
subinter中有一个方法
subweb调用subinter中的方法
运行：
进入main模块中
  1.执行gradle build
  2.执行gradle tomcatRun
  浏览器访问http://localhost:8080/subWeb
