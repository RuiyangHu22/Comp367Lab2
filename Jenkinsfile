pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Checkout source code from Git
                git 'https://github.com/RuiyangHu22/Comp367Lab2.git'

                // Build the Maven project
                bat 'mvn clean install'
            }
        }
    }
}
