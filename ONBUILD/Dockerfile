FROM almalinux
RUN yum install nginx -y
#when image creator is running this below command will not run, when someone else tries to use your image then it will run
ONBUILD ADD simple.txt /tmp/
#ONBUILD RUN yum install