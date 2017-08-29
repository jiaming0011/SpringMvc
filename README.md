# SpringMvc学习小结
### 有关创建maven项目
创建maven项目，进入控制台界面，cd进入自己要创建工程的目录，在命令行输入以下命令：<br>
mvn archetype:generate -DgroupId=? -DartifactId=? -DarchetypeArtifactId=maven-archetype-webapp<br>
两个问号是你自己决定输入的<br>
  -DgroupId　　　组织标识（包名）  

-DartifactId　　　项目名称  <br>
maven-archetype-webapp  表示这是一个web项目<br>
完成之后直接在eclipse环境下import进新建的maven项目就行啦
