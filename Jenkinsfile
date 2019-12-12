node{
  
  stage('SCM Checkout')
  {
    git 'https://github.com/chaithrashankarappa/test2.git'
  }
  stage('compile package')
  {
    sh 'mvn package'
  }
}
