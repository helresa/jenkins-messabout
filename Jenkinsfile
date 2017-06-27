pipeline {
  agent any
  stages {
    stage('Hello') {
      steps {
        echo 'Hello'
      }
    }
    stage('Pull Code') {
      steps {
        git(url: 'https://helresa@bitbucket.org/goodlord/goodlord.git', branch: 'master', credentialsId: 'bitbucket')
      }
    }
  }
}