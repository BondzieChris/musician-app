pipeline{
    agent any
    stages{
        stage("Build Stage"){
            steps{
               nodejs(nodeJSInstallationName: 'NodeJS.12', configId: '<config-file-provider-id>') {
                    sh 'node -v'
                    sh 'npm -v'
                }
            }

        }
    }

}
