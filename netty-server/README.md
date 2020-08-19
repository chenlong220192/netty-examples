# netty server

# 打包
```
./gradlew clean && ./gradlew release
```
# 运行
```
java -jar ./build/libs/netty-server-1.0.jar <port>
```

注意：build.gradle中配置了本地仓库，构建前可以直接删除或指定私有仓库连接。
