pipeline {
  agent any
  stages{
     stage('clone'){
      steps {
       git credentialsId: '940d63f8-03d3-4e44-9eb0-8b74142dfd4f', url: 'https://github.com/Naaz2005/N48.git'
      }
    }
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
