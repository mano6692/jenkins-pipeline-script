# jenkins-pipeline-script
this repo contain 2 types of declarative peipeline script 
for this script to run without error

install owasp dependency check version 8.4.0
install jdk version 17

and install trivy in ubuntu os 

sudo apt-get install wget apt-transport-https gnupg lsb-release

wget -qO - https://aquasecurity.github.io/trivy-repo/deb/public.key | sudo apt-key add -

echo deb https://aquasecurity.github.io/trivy-repo/deb $(lsb_release -sc) main | sudo tee -a /etc/apt/sources.list.d/trivy.list

sudo apt-get update

sudo apt-get install trivy
