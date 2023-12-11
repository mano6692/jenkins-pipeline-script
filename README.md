# jenkins-pipeline-script
this repo contain 2 types of declarative peipeline script 
for this script to run without error

install owasp dependency check version 8.4.0
install jdk version 17
and install trivy in ubuntu os 

$ sudo vim /etc/yum.repos.d/trivy.repo
[trivy]
name=Trivy repository
baseurl=https://aquasecurity.github.io/trivy-repo/rpm/releases/$releasever/$basearch/
gpgcheck=0
enabled=1
$ sudo yum -y update
$ sudo yum -y install trivy
