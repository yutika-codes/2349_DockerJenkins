pipeline{
agent {
  dockerfile {
    filename 'Dockerfile'
  }
}

  stages{
    stage{
      stage('Clean workspace '){
        steps{
          cleanWS()
        }
      }
    }
  stage('clone github repo'){
    steps{
      git branch: 'main',
          url: ''
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
