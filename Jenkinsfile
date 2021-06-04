pipeline {
    agent { label 'master' }
    stages {
        stage('build & run') {
            steps {
                cd jenkinsCI
                mvn clean install
            }
        }
    }
}

