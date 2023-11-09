pipeline {
  agent any
stages {
  stage('maven install') {
    steps {
      git
      withMaven(globalMavenSettingsConfig: '', jdk: '', maven: '', mavenSettingsConfig: '', traceability: true) {
    sh 'mvn clean instal'
}
    }
  }

}
}
