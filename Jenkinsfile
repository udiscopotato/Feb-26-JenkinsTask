pipeline {
  agent any
  
  stages {
    stage("SCM") {
      steps {
        git 'https://github.com/udiscopotato/Feb-26-JenkinsTask.git'
      }
    }
    stage("Python") {
      steps {
        sh "python3 main.py"
      }
    }
    stage("Java") {
      steps {
        sh "java Demo.java"
      }
    }
  }
}
