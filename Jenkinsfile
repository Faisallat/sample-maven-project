pipeline {
  agent any
  stages {
  stage('Maven install') {
    steps {
      withMaven(globalMavenSettingsConfig: 'null', jdk: 'null', maven: 'maven3', mavenSettingsConfig: 'null')  {
      sh 'mvn clean install'
}
    }

}
  }
}
