# 开发指南

```bash
# code ~/.zshrc
# 修改为java-17
# 设置代理
export http_proxy=http://127.0.0.1:10818
export https_proxy=http://127.0.0.1:10818
# 查询具体的任务信息的帮助
./gradlew help --task bootRun
# 启动Spring Boot
./gradlew bootRun
# gradle bootRun
# 编译可执行jar包
./gradlew bootJar
# 清理build的任务：clean
./gradlew clean
# 执行测试的任务：test
./gradlew test
```
