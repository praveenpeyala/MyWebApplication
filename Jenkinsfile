pipeline {
  agent any
 tools{
        jdk  'jdk11'
        maven  'maven3'
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
