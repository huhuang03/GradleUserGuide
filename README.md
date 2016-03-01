# Gradle 官方文档
* 语言：英文
* 状态：在读
* 描述：C语言的一本初级书
* 在线地址：https://docs.gradle.org/current/userguide/userguide.html
* 练习工程地址：https://github.com/huhuang03/point_in_c.git

# Gradle Wrapper
执行gradle命令，如果机器里面有gradle wrapper指定版本的gradle，则会委托给制定版本的gralde（既gradlew）。如果没有，则会下载。

如果直接执行gradlew命令，则会忽略机器里面原有的gradle所有版本。

如果没有gradlew，则按照正常的gradle执行了。执行的是你当前环境里的gradle版本。
