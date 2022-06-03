pipeline {
  agent any
  stages {
  stage('Maven install') {
    steps {
      withMaven(globalMavenSettingsConfig: 'null', jdk: 'null', maven: 'Maven3', mavenSettingsConfig: 'null') {
      sh 'mvn clean install'
}
    }

}
  }
}
