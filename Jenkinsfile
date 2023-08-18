pipeline{
  agent any
  stages{
    stage("Hello"){
      steps{
        scripts{
        git url:'https://github.com/harikesh12/CentralRepo.git' , branch:'master'
        }
 steps{
        sh 'cat README.md'
        }
        
      }
    }
  }
}
