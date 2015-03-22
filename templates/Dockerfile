FROM gitinsky/oracle-java-8:0.1.0
MAINTAINER Git In Sky <support@gitinsky.com>

RUN \
  cd / && \
  wget http://apache-mirror.rbc.ru/pub/apache/hbase/hbase-1.0.0/hbase-1.0.0-bin.tar.gz && \
  tar xvzf hbase-1.0.0-bin.tar.gz && \
  rm -f hbase-1.0.0-bin.tar.gz && \
  ln -s /hbase-1.0.0 /hbase && \
  useradd -m hadoop
