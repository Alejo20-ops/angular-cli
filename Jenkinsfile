pipeline {
  agent any
  stages {
    stage('paso1') {
      steps {
        bat '''npm install -g @angular/cli
npm install
ng build --prod'''
      }
    }

  }
}
