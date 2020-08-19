pipeline {
    agent any

    stages {
        stage('read') {
            steps {
                script {
                def datas = readYaml (file: 'test.yaml')
                
                }
                echo datas.name.toString()
            }
        }
    }
}
