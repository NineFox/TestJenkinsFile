pipeline {
    agent any
    stages {
        stage('archive file') {
            steps {
                echo 'hello world'
                def artifactsFilePath = archiveArtifacts artifacts: '**/src/*', followSymlinks: false
                echo artifactsFilePath
            }
        }
    }
}
