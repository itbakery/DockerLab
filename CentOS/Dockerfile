FROM centos

RUN yum -y install epel-release
RUN rpm -ivh http://pkgs.repoforge.org/rpmforge-release/rpmforge-release-0.5.3-1.el7.rf.x86_64.rpm
RUN yum -y update
RUN yum -y install python34 python34-devel  python34-PyYAML openssl-devel vim
RUN curl https://bootstrap.pypa.io/get-pip.py | python3.4 - 
RUN yum -y clean all
