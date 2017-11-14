pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        cbtSeleniumTest(operatingSystem: 'windows 8', browser: 'firefox', resolution: '800*600')
      }
    }
  }
}