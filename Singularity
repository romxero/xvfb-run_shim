Bootstrap: docker
From: ubuntu:bionic

%labels
Author "Randall Cab White - rcwhite@stanford.edu"


#########
#%setup
#########

#Downlaod packages
%post
  apt-get -ym update
  apt-get -ym install xvfb imagej openjdk-11-jdk openjdk-11-jre 

%environment
#  export IMAGE_NAME="firefox"
%runscript
#	firefox
