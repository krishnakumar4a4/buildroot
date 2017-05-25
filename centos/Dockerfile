#Set the base image
FROM centos:7

#Dockerfile author/maintainer
MAINTAINER krishna kumar thokala

#Installing dependent packages 
RUN yum install -y make which gcc* nurses-devel flex bison unzip make perl file patch wget rsync bc git bzip2 perl-devel perl-data-dumper perl-Thread-Queue

#Getting buildroot image
RUN curl -O https://buildroot.uclibc.org/downloads/buildroot-2017.02.2.tar.bz2

#Untar buildroot image
#RUN tar -xzf buildroot-2017.02.2.tar.bz2
