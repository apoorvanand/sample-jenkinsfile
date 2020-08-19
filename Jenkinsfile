pipeline {
    agent any

    stages {
        stage('read') {
            steps {
                def datas = readYaml text: """
            name: TestFile
            servers:
                - name: myserver
                  host: myhost.world.com
                  scheme: https
            """
                assert datas.name =="myserver"
            }
        }
    }
}
