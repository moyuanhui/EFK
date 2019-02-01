FROM huisebug/sec_re:fluentd-elasticsearch-2.4.0
RUN \
    apt-get update -y && apt-get install ruby-dev -y && \
    gem install fluent-plugin-s3 && \
    apt-get clean
# 此镜像用于fluentd-server-s3服务
