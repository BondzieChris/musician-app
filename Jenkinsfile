pipeline{
    agent any
    stages{
        stage("Build Stage"){
            steps{
               nodejs('NodeJS.12') {
                    sh 'node -v'
                    sh 'npm -v'
                }
            }

        }
    }

}
