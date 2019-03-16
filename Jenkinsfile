pipline {
  agent any
  stages {
    stage ('buld') {
      steps {
        echo 'hello, my freind'
        sh './gradlew build --no-daemon'
        archiveArtifcts artifact: 'dist/trainSchedule.zip'
      }
    }
  }
}
