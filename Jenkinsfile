pipeline {
  agent any
stages {
  stage('maven install') {
    steps {
      git
      withMaven(maven: 'maven3')(globalMavenSettingsConfig: '', jdk: '', maven: '', mavenSettingsConfig: '', traceability: true) {
    sh 'mvn clean instal'
}
    }
  }

}
}
