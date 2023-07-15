pipeline {
    agent any
    stages {
        stage('Check Maven') {
            steps { 
                sh 'whoami && echo $PATH'
        }
   }
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
