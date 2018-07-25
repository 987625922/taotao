# 淘淘商城项目第一期
#### 教程链接：https://blog.csdn.net/yerenyuan_pku/article/details/72669269
#### https://blog.csdn.net/yerenyuan_pku/article/details/72672138

##### 遇到的错误
###### 1.run taotoa-web时报 Non-resolvable parent POM: Could not find artifact...
###### 在taotao-web工程的pom.xml的parent标签中添加<relativePath>../taotao-parent</relativePath>内容

###### 2.run taotao-manager时报 Failed to execute goal on project ...: Could not resolve dependencies for project ...
###### 把工程taotao-parent和taotao-manager工程右击 RUN AS -> maven install

### 简介：
#### 最近在复习java ssm框架，就看到淘淘商城系列（https://blog.csdn.net/column/details/15737.html?&page=5）,想着博主没有发布源码，我就一步步把我写的源码发布到github上供大家下载学习
