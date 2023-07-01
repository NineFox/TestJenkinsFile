pipeline {
    agent any
    stages {
        stage('archive file') {
            steps {
                echo 'hello world'
                archiveArtifacts artifacts: '**/src/*', followSymlinks: false
            }
        }
    }
}
