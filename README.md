# jenkins
#steps to install jenkins on RHEL 9
sudo curl -o /etc/yum.repos.d/jenkins.repo     https://pkg.jenkins.io/redhat-stable/jenkins.repo
sudo rpm --import https://pkg.jenkins.io/redhat-stable/jenkins.io-2023.key
sudo yum install fontconfig java-21-openjdk
sudo yum install jenkins -y
sudo systemctl start jenkins
sudo systemctl enable jenkins
