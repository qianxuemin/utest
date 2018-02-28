# karma+jasmine搭建单元测试环境步骤
- npm init   初始化package.json
- npm install karma-cli -g
- npm install karma --save-dev  全局安装
- npm install karma-jasmine --save-dev 
- npm install karma-chrome-launcher --save-dev
- npm install jasmine-core --save-dev
- npm install karma-coverage
- karma init 初始化karma配置文件karma.conf.js
- karma start  开始测试

# selenium-webdriver 进行e2e测试步骤
- npm install selenium-webdriver
- 新建测试文件如 e2e.es 编写测试代码
- 下载浏览器驱动到项目根目录
- 执行 node e2e.es