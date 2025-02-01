pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'building stage'
                sh 'git --version'
                sh 'git clone https://github.com/igorcibotarescu/sensors.git'
            }
        }
    }
}
