node{
  stage('SCM Checkout'){
    git 'https://github.com/rachit-gupta95/second-demo-project'
  }
  stage('Compile-package'){
    def mvnHome = tool name: 'Maven_3.8.5', type: 'maven'
    sh "${mvnHome}/bin/mvn package"
  }
  
}
