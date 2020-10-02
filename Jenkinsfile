pipeline {
    agent any

    stages {
        stage('checkout') {
            steps {
                git branch: 'development', credentialsId: '723826cf-f009-46f6-bf4e-14271926ddb1', url: 'https://github.com/dheerajpure/springboot-01-crud.git'
            }
        }
    }
}
