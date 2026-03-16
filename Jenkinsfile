pipeline {
  agent any

  stages {
    stage('Clone') {
      steps {
        git branch : 'main' ,url : "https://github.com/Chinmayee-R12/laa3.git"
      }
    }
    stage('Run script') {
      steps {
        sh 'python3 script.py'
      }
    }
  }
}
  
