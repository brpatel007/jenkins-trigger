pipeline {
  agent none
  options { disableConcurrentBuilds() }
  stages {
    stage ("git clone") {
      agent { label "master" }
      steps {
        echo "test"
      }
    }
  }
}
