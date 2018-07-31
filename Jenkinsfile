pipeline {
  agent any
  stages {
    stage('creazioneJenkinfile') {
      steps {
        echo 'creazione di jenksuccio'
      }
    }
    stage('compilazione del codice') {
      steps {
        bat './mvnw spring-boot:run'
      }
    }
  }
}
