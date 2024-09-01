pipeline{
agent {
  dockerfile {
    filename 'Dockerfile'
  }
}

  stages{
      stage('Clean workspace '){
        steps{
          cleanWS()
        }
      }
    
  stage('clone github repo'){
    steps{
      git branch: 'main',
          url: 'https://github.com/yutika-codes/2349_DockerJenkins.git'
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
