FROM centos:6

RUN mkdir /jobs && \
    mkdir /software && \
    yum update -y && \
    yum groupinstall -y development && \
    yum install -y wget && \
    yum install -y zlib-dev openssl-devel sqlite-devel bzip2-devel && \
    wget http://www.python.org/ftp/python/2.7.6/Python-2.7.6.tar.xz && \
    yum install -y xz-libs && \
    xz -d Python-2.7.6.tar.xz && \
    cd Python-2.7.6 && \
    ./configure --prefix=/usr/local && \
    make && \
    make altinstall && \
    export PATH="/usr/local/bin:$PATH"