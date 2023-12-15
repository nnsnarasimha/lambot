# sonarqube pipeline


https://raw.githubuserconteX SonarScanner for Jenkins|S x sonarqube-pipeline Config x| demoapp-project
X Users - Administration
x | i Instances | EC2 Manageme x| +
+ → C @ raw.githubusercontent.com/ravdy/DevOps/master/sonarqube/Jenkinsfile
pipeline(
agent any
environment
PATH = "§PATH: /opt/apache-maven-3.8.2/bin"
stagest
stage(GetCode'f
steps(
git https://github.com/ravdy/javaloginapp.git'
｝
stage('Build")
steps(
sh 'mon clean package'
//
//
stage('SonarQube analysis') {
def scannerHome = tool 'SonarScanner 4.0';
stepst
withSonarQubeEnv ('sonarqube-8.9') {
// If you have configured more than one global server connection, you can specify its name
sh "$(scannerHome) /bin/sonar-scanner* sh
"myn sonar: sonar"
0-0 x
★★v：
Q
