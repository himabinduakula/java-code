pipeline {
  agent any
  stages {
    stage('gietcode') {
      steps {
        git(url: 'https://github.com/himabinduakula/java-code.git', branch: 'master', changelog: true)
      }
    }

    stage('maven') {
      steps {
        sh 'mvn package'
      }
    }

  }
}