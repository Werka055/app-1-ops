pipeline {
    agent any
    parameters {
        booleanParam(name: 'DEPLOY', defaultValue: true, description: 'Czy uruchomić etap wdrożenia?')
    }
    stages {
        stage('Checkout') {
            steps {
                git url: 'https://github.com/PeterPorzuczek/TimeRiddle.git', branch: 'master'
            }
        }
    }
}
