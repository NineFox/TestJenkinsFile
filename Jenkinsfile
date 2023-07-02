pipeline {
    agent any
    stages {
        stage('prtint env') {
            steps {
                sh "printenv"
            }
        }
        stage('archive file') {
            steps {
                echo 'hello world'
                archiveArtifacts artifacts: '**/src/*', followSymlinks: false
            }
        }
    }
}
