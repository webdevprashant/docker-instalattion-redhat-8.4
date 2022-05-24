Docker install in redhat 8 


Step1 :- Remove Older one

sudo  yum remove docker \
                  docker-client \
                  docker-client-latest \
                  docker-common \
                  docker-latest \
                  docker-latest-logrotate \
                  docker-logrotate \
                  docker-engine -y
                  
Step2:- yum install yum-utils -y

Step3 :- Download docker repo and paste in /etc/yum.repos.d/

Step4:- yum install docker-ce -y
