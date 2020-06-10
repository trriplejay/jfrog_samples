pipeline {
    agent { docker { image 'node:6.3' } }
    parameters {
      string(name: 'runNumber', defaultValue: '0', description: 'JFrog Pipelines Run Number')
    }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
    }
}
