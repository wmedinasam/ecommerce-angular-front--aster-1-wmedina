node {
  stage('SonarQube Analysis') {
    def scannerHome = tool 'SonarQubeLocal';
    withSonarQubeEnv() {
      sh "${scannerHome}/bin/sonar-scanner"
    }
  }
}