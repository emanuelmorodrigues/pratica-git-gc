pipeline {
  agent any
  stages {
    stage('Inicializar / Mensagem') {
      steps {
        echo 'Esta é uma pipeline de inicialização'
        mail(subject: '[Jenkins] Inicializando Pipeline', body: 'Estamos realmente inicializando a pipeline')
      }
    }

  }
}