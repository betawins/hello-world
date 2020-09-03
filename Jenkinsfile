pipeline {
    agent { maven }

    tools {
        // Install the Maven version configured as "M3" and add it to the path.
        maven "mvn_home"
    }

    stages {
        stage('git chekout') {
            steps {
                // Get some code from a GitHub repository
                git 'https://github.com/betawins/hello-world.git'
            }
       stage('compile'){
      steps{
   sh 'mcn compile'
}
}
        }
    }
}
