pipeline {
  agent any

  stages {
      stage('Build Artifact') {
            steps {
              sh "mvn clean package -DskipTests=true" //so that they can be downloaded later someting else tis for infosometing new bro
              archive 'target/*.jar' 
            }
        }   
    }
}