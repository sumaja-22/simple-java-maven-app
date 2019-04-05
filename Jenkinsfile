pipeline {
    agent {
        docker {
            image 'maven:3-alpine' 
           /* args '-v /root/.m2:/home/user1/GitHub/simple-java-maven-app.m2'*/ 
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -e -B -DskipTests clean package' 
            }
        }
    }
}
