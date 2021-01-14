node{
stage('SCM Checkout')
{
git 'https://github.com/msabareesh92/java.git'
}
stage('compile')
{
 def Home=tool name: 'Maven 3', type: 'maven'
sh "${Home}/bin/mvn package"
}
}
