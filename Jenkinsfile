node{
stage('SCM Checkout')
{
git 'https://github.com/msabareesh92/java.git'
}
stage('compile')
{
 def Home=tool name: 'maven3', type: 'maven'
sh "${Home}/bin/mvn package"
}
}
