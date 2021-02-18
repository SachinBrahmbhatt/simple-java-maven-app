pipeline {
    agent any

    stages {
        stage ('Compile Stage') {
            steps {
                sh 'mvn package install;'
            }
        }
        stage ('Run Stage') {
            steps {
                sh 'java -jar target/*.jar'
            }
        }
    }
}
