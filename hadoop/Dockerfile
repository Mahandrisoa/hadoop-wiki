FROM sequenceiq/hadoop-docker:2.7.1

# Copy custom configurations into the image
COPY ./configs/core-site.xml $HADOOP_PREFIX/etc/hadoop/
COPY ./configs/hdfs-site.xml $HADOOP_PREFIX/etc/hadoop/
