pipeline {
    agent any

    stages {
        stage('read') {
            steps {
                script {
                def datas = readYaml (file: './test.yaml')
                echo datas.name.toString()
                }
            }
        }
           stage('write') {
             steps {
                script {
                def map=['name':'TestFile']
                map.server = [['name': 'myserver', 'host': 'myhost.world.com', 'scheme': 'https'],['name': 'myserver2', 'host': 'myhost.world.2com', 'scheme': 'https']]
                writeYaml file: 'datas.yaml', data: map
                def read = readYaml file: 'datas.yaml'
                }
            }
        }
    }           
}
