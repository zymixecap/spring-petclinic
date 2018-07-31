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
        echo 'inizio compilazione codice sorgente'
        bat './mvnw spring-boot:run'
        echo 'ho terminato di compilare il codice'
      }
    }
  }
}
