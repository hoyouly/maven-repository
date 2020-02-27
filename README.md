 repository  这个目录下面就是存放我们deploy的项目相关信息 ,也就是说我们项目deploy指定的目录，就是这里



约定将项目中的snapshot版，deploy到仓库的 snapshot分支上
约定将项目中的release版，deploy到仓库的 release分支上
master分支管理所有的版本



## deploy项目到本地仓库
mvn clean deploy -Dmaven.test.skip  -DaltDeploymentRepository=self-mvn-repo::default::file:/Users/hoyouly/llll/maven-repository/repository
