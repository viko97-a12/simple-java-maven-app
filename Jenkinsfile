pipeline {
    agent {
        dockerContainer {
            image 'maven:3.9.3-eclipse-temurin-11' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
