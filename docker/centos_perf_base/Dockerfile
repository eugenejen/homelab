FROM centos

WORKDIR /
RUN yum update -y && \
    yum install -y perf &&\
    yum install -y lsof && \
    yum install -y man-pages && \
    yum install -y man-db && \
    yum install -y strace && \
    yum install -y ltrace && \
    yum install -y tcpdump && \
    yum install -y sysstat && \
    yum install -y bpftool && \
    yum install -y bpftrace && \
    yum install -y net-tools && \
    yum install -y git && \
    yum install -y which && \
    yum clean all && \
    rm -rf /var/cache/yum

WORKDIR /opt
RUN git clone https://github.com/brendangregg/perf-tools.git



