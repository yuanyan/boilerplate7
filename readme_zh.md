# [Boilerplate7]

Boilerplate7 is a professional front-end template that helps you build fast, robust, adaptable, and future-proof websites. Spend more time developing and less time reinventing the wheel.

This project is the product of many years of iterative development and combined community knowledge. It does not impose a specific development philosophy or framework, so you're free to architect your code in the way that you want.

Boilerpalte7 是面向前端开发的模版框架，辅助开发者快速建立项目基础骨架。
## Quick start

Clone the git repo - `git clone git://github.com/bear7/boilerplate7.git` - or [download it](https://github.com/bear7/boilerplate7/zipball/master)


## Features

* HTML5 ready. Use the new elements with confidence.
* Cross-browser compatible (Chrome, Opera, Safari, Firefox 3.6+, IE6+).
* Designed with progressive enhancement in mind.
* CSS normalizations and common bug fixes.
* IE-specific classes for easier cross-browser control.
* A default print stylesheet, performance optimized.
* Mobile browser optimizations.
* Protection against any stray `console.log` causing JavaScript errors in IE6/7.
* The latest jQuery via CDN, with a local fallback.
* A custom Modernizr build for feature detection.
* An optimized Google Analytics snippet.
* Apache server caching, compression, and other configuration defaults for Grade-A performance.
* Cross-domain Ajax and Flash.
* "Delete-key friendly." Easy to strip out parts you don't need.
* Extensive inline and accompanying documentation.


### Major components:

* jQuery
* Normalize.css
* HTML5-Boilerplate


### 安装步骤

1. 从http://nodejs.org/下载安装nodejs，在一些公司里需要设置代理才可以正常使用npm：
    1. 在系统变量里新建HTTP_PROXY 或 http_proxy 配置，如 HTTP_PROXY= http://proxy.example.com:8080
    2. npm 的默认registry 为 https://registry.npmjs.org/ ，我们修改可以正常访问的国内镜像地址 npm config set registry http://registry.npmjs.vitecho.com/
2. 从npm安装grunt： npm install grunt
3. 安装grunt常用的扩展任务，如Boilerplate7中已经使用的requrejs与less任务（更多任务介绍访问https://github.com/gruntjs/grunt-contrib）： npm install grunt-contrib
4. 在windows下grunt.cmd