FROM maven:3.8.1-openjdk-11-slim

COPY sources.list /etc/apt/sources.list

# 直接覆盖 Maven 配置文件
COPY settings.xml /usr/share/maven/conf
