pipeline {
    agent {
        docker {
            image 'maven:3-alpine' 
          args '-v $HOME/.m2:$HOME/.m2'
        }
    }
}
    /*stages {
        stage('Build') { 
            steps {
                sh 'mvn -e -B -DskipTests clean package' 
            }
        }
    }
}
