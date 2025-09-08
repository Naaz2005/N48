pipeline {
  agent any
  stages{
    stage('compile'){
      steps {
        bat'javac HelloWorld.java'
      }
    }
    stage('run') 
    {steps {
      bat 'java HelloWorld'
    }
    }
  }
}
