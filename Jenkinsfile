pipeline {
    agent any

    environment {
        DISABLE_AUTH = 'true'
        DB_ENGINE    = 'sqlite'
    }

    stages {
        stage('Build') {
            steps {
                
deploy adapters: [tomcat9(path: '', url: 'http://18.218.191.175:8082')], contextPath: 'helloworld', war: '**/*.war'
                sh 'printenv'
            }
        }
    }
}
