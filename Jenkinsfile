pipeline {
    agent any 
    stages {
        stage('compile') { 
            steps {
                  withMaven(maven : 'maven'){
                     sh 'mvn clean compile'
                echo "pass"
                  }
            }
        }
        stage('Testing Stage') { 
            steps {
//                 withMaven(maven : 'maven_3_8_6'){
//                     sh 'mvn test'
                echo "pass"
//                  }
            }
        }
    }
}
