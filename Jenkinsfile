pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sh '/var/jenkins_home/apache-maven-3.8.6/bin/mvn -B -DskipTests clean package' 
            }
        }
    }
}
