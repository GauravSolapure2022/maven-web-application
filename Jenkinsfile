pipeline {  

    agent any
        
    tools{
        maven "Maven-3.9.0"
    }
    stages {
        stage('Clone') {
            steps {
               git 'https://github.com/GauravSolapure2022/maven-web-application.git'
            }
        }
        stage('Build') {
            steps {
               sh 'mvn clean package'
            }
        }
    }
}
