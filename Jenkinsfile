pipeline{
  
  stages{
  stage('clone'){
    steps{
      bat '''git clone https://github.com/yutika-codes/2349_DockerJenkins.git'''
    }
  }
    stage('Build'){
      steps{
        bat '''docker build -t latest'''
      }
    }
    stage('Run'){
      steps{
        bat '''docker run'''
      }
    }
    }
  }
