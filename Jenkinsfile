node{
  stage('SCM Checkout'){
    git 'https://github.com/Codehunter-py/my-app'
  }
  stage('Compile-Package'){
        sh 'mvn package'
  }
}
