打包 跳过测试
mvn clean package -Dmaven.test.skip
执行
java -jar helloworld-0.0.1-SNAPSHOT.jar



spring boot默认会打可执行的jar包，这个jar的结构和普通的是不一样的，
里面会包含所依赖的各种jar，同时也会有web容器，因此不再需要容器，直接就能运行。



http://localhost:8080/hello
http://localhost:8080/hello-spring/hello
因为项目就是发布到ROOT，即直接发布在/的。