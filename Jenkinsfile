pipeline {
  agent any
  stages {
    stage('stage 1') {
      steps {
        bat(script: 'echoFile.bat', encoding: '@echo off echo %USERNAME% echo %DATE%')
      }
    }
  }
}