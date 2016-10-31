FROM centos:6

# PYTHON DEPENDENCIES
RUN yum -y update && yum groupinstall -y 'development tools' \
    epel-release \
    git \
    gcc

# PYTHON
RUN yum -y update && yum install -y \
    python-devel \
    python2.7 \
    python3.5 \
    python-pip \
    python-nose \
    python-wheeel && yum upgrade python-setuptools
