pipeline { 
    agent any
    
    tools {
        maven 'maven3'
        jdk 'jdk17'
    }

    stages {   
        stage('Package') {
            steps {
                sh "mvn package"
            }
        }
    }
}
