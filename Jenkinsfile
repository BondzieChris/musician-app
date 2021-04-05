pipeline{
    agent any
    stages{
        stage("Node Stage"){
            steps{
               nodejs('NodeJS.12') {
                   bat 'yarn -v'
                    bat 'node -v'
                    bat 'npm -v'
                }
            }

        }
    }
    stages{
        stage("Maven/Java Stage"){
             steps{
               withMaven {
                 bat 'mvn -v'
                 bat 'java -version'
                }
            }

        }
    }

}
