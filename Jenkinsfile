node{
  
  stage('SCM Checkout')
  {
    git 'https://github.com/chaithrashankarappa/test2.git'
  }
  stage('compile package')
  {
    def mvnHome = tool name: 'maven3', type: 'maven'
    sh "${mvnHome}/bin/mvn package"
  }
}
