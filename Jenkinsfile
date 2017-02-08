pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'hello'
      }
    }
    stage('Tier 1') {
      steps {
        build(job: 'ipa-provision-functional-services-pytest', wait: true)
      }
    }
  }
}
