pipeline{
  agent any
  stages{
    stage("Hello"){
      steps{
        git url:'https://github.com/harikesh12/CentralRepo.git' , branch:'master'
        sh 'cat README.md'
      
      }
    }
  }
}
