pipeline{
    agent any
    stages{
        stage("Build Stage"){
            steps{
               nodejs('NodeJS.12') {
                   bat 'yarn -v'
                    bat 'node -v'
                    bat 'npm -v'
                }
            }

        }
    }

}
