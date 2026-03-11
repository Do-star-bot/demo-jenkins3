pipeline{
  agent any
  
  stages{

    stage('Clone'){
      steps{
        git url:'https://github.com/Do-star-bot/demo-jenkins3.git',
          branch:'main'
      }
    }

    stage('Run Script'){
      steps{
        sh 'chmod +x script.sh'
        sh './script.sh'
      }
    }
  }
}
