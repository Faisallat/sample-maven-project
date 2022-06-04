pipeline {
  agent any
  stages {
  stage('Maven install') {
    steps {
      withMaven(maven: 'maven3')  {
      sh 'mvn clean install'
}
    }

}
  }
}
