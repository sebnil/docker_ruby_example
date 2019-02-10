pipeline
{
  agent {
    docker {
      image 'ruby:2.3.1'
    }
  }
  stages {
    stage("Test Ruby") {
      steps {
        sh "ruby --version"
      }
    }
  }
}
