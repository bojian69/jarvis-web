UI库使用 https://element.eleme.cn/#/zh-CN/
框架使用 https://panjiachen.github.io/vue-element-admin-site/zh/feature/component/rich-editor.html


1.本地开发修改vue.config.js proxy代理即可访问接口（查找TODO）
2.登录，权限已经调通（查找TODO）
  权限配置页面 store/model/permission下 filterAsyncRoutes（查找TODO）
3.a添加新页面,views目录下即可添加创建
  b然后再router/index.js   asyncRoutes添加页面对象配置（查找TODO）
4.添加接口请求
   在api目录下，添加文件/或直接修改文件；
   原则上页面名称  和api目录下名称对应，便于开发查找
   通用类接口在common下添加

  
  
