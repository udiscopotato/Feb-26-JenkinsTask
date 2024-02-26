pipeline {
  agent any
  
  stages {
    stage("SCM") {
      git 'https://github.com/udiscopotato/Feb-26-JenkinsTask.git'
    }
    stage("Python") {
      sh "python3 main.py"
    }
    stage("Java") {
      sh "java Demo.java"
    }
  }
}
