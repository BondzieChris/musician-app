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
             steps{
               withMaven {
                 bat 'mvn -v'
                 bat 'java -version'
                }
            }

        }
    }

}
