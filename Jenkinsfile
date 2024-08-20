pipeline {
    agent any
    environment {
        JAVA_HOME = '/var/run/openjdk-17'
    }
    stages {
        stage('Build') {
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
