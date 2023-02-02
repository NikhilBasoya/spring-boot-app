pipeline {
  agent any

  stages {
    stage ('Build') {
      steps {
        withMaven(maven : 'maven-3.6.3')
        {
          sh 'mvn clean package'
        }
      }
    }
  }
}
