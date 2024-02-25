FROM docker.wso2.com/wso2am:4.2.0.0
LABEL maintainer="WSO2 Docker Maintainers <dev@wso2.org>"

ARG MYSQL_CONNECTOR_VERSION=8.0.17

ADD --chown=wso2carbon:wso2 https://repo1.maven.org/maven2/mysql/mysql-connector-java/${MYSQL_CONNECTOR_VERSION}/mysql-connector-java-${MYSQL_CONNECTOR_VERSION}.jar ${WSO2_SERVER_HOME}/repository/components/dropins/
