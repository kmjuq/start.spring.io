# 启动步骤
`mvn clean install` 安装 `start.spring.io` 到本地maven仓库.
如果构建失败，`cd start-client` 清除缓存 `rm -rf .cache node_modules`
在`start-site`目录启动 `mvn spring-boot:run`