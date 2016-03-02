FROM centos

RUN yum -y install epel-release
RUN yum -y install http://pkgs.repoforge.org/rpmforge-release/rpmforge-release-0.5.3-1.el7.rf.x86_64.rpmm

RUN yum -y install python34 python34-devel python34-PyYaml \
      && curl https://bootstrap.pypa.io/get-pip.py | python3.4 - \
      && yum -y clean all
