pipeline {
  agent any
  stages {
    stage('echo') {
      steps {
        echo 'hello from Ben'
      }
    }

  }
  triggers {
    cron('H/15 * * * *')
  }
}