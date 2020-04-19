
# 构建命令

mvn package

# 本地启动

java -jar target/spring-boot-docker-1.0.jar

# image制作

docker build . -t springboot

# docker run

docker run --rm -p 8080:8080  springboot
