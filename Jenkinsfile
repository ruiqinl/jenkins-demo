pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('build') {
            steps {
                sh './dummy.sh'
                sh '''
                  echo "multi line shell steps work"
                  ls -alh /
                '''
            }
        }
    }
}
