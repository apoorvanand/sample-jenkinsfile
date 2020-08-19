pipeline {
    agent any

    stages {
        stage('read') {
            steps {
                script {
                def datas = readYaml text: """
            servers:
                - name: myserver
                  host: myhost.world.com
                  scheme: https
            """
                assert datas.servers.name =="myserver"
                }
            }
        }
    }
}
