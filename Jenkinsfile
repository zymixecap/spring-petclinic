pipeline {
  agent any
  stages {
    stage('creazioneJenkinfile') {
      steps {
        echo 'creazione di jenksuccio'
        sh '''#!bash

./mvnw spring-boot:run'''
      }
    }
  }
}