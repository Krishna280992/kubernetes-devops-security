pipeline {
  agent any

  stages {
      stage('Build Artifact') {
            steps {
              sh "mvn clean package -DskipTests=true" //so that they bro
              archive 'target/*.jar' 
            }
        }   
    }
}