pipeline {
  agent { label 'awslx-slave1' }
  stages {
    stage('CHECK') {
      steps {
        fileExists 'firstjob'
        sh '''#!/bin/bash
pwd
echo $PATH'''
      }
    }

  }
}
