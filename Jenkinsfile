pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                git branch: 'main', url: 'https://github.com/RuiyangHu22/Comp367Lab2.git'
                
                sh 'mvn clean package'
            }
        }
    }
}
