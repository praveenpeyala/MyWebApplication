pipeline {
  agent any
  tools {
    maven 'maven-3.6.3' 
  }
  stages {
    stage ('Setup') {
      steps {
        git branch: 'argroups', url: 'https://github.com/RAMARJUN397/MyWebApplication.git'
      }
    }
    stage ('Compile') {
      steps {
        sh 'mvn compile'
      }
    }
  }
}
