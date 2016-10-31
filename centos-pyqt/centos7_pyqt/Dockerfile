FROM daemonecles/pythonbase-centos:centos7

RUN yum -y update

# PYTHON DEPENDENCIES
RUN yum install -y cmake \
    wget \
    centos-release-scl \
    zlib-devel \
    openssl-devel \
    sqlite-devel \
    bzip2-devel \
    xz-libs \
    epel-release

# PYQT
RUN yum -y update && yum install -y qt-devel \
    qt5-qtbase-devel \
    qt5-designer \
    python-pyside \
    PyQt4 && \
    yum install -y python-pip && \
    pip install pip -U && \
    pip2.7 install python-qt5

