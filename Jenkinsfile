pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('build') {
            steps {
                sh 'echo "hello world"'
                sh '''
                  echo "multi line shell steps work"
                  ls -alh /
                '''
            }
        }
    }
}
