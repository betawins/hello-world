pipeline {
    agent any

    tools {
        // Install the Maven version configured as "M3" and add it to the path.
        maven "mvn_home"
    }

    stages {
        stage('checkout') {
            steps {
                // Get some code from a GitHub repository
                git 'https://github.com/betawins/hello-world.git'
            }

        }
        stage('build') {
            steps {
                // Get some code from a GitHub repository
               sh 'mvn compile'
            }

        }
    }
}
