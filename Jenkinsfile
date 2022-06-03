pipeline {
  agent any
  stages {
  stage('Maven install') {
    steps {
      withMaven(maven: 'Maven3') {
      sh 'mvn clean install'
}
    }

}
  }
}
