# grunt


a. 安装grunt

npm install grunt --save-dev

b. Gruntfile

包括“wrapper”函数，项目与任务配置，加载grunt插件和任务，自定义任务

grunt-contrib-ugligy插件中的 uglify 任务要求它的配置被指定在一个同名属性中。

通过定义 default 任务可以让 Grunt 默认执行一个或多个任务。

c. Grunt 配置

Grunt 的task配置都是在 Gruntfile中的 grunt.initConfig方法中指定的。

在一个任务配置中，options 属性可以用来指定覆盖内置属性的默认值。

Grunt 有grunt.file.readJSON 和 grunt.file.readYAML 2种方法来导入外部数据。
