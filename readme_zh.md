# [Boilerplate7]

Boilerpalte7 是面向前端开发的模版框架，辅助开发者快速建立项目基础骨架。

### 安装步骤

1. 从http://nodejs.org/下载安装nodejs，在一些公司里需要设置代理才可以正常使用npm：
    1. 在系统变量里新建HTTP_PROXY 或 http_proxy 配置，如 HTTP_PROXY= http://proxy.example.com:8080
    2. npm 的默认registry 为 https://registry.npmjs.org/ ，我们修改可以正常访问的国内镜像地址 npm config set registry http://registry.npmjs.vitecho.com/
2. 从npm安装grunt： npm install grunt
3. 安装grunt常用的扩展任务，如Boilerplate7中已经使用的requrejs与less任务（更多任务介绍访问https://github.com/gruntjs/grunt-contrib）： npm install grunt-contrib
4. 在windows下grunt.cmd