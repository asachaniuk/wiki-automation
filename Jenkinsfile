pipeline {
    agent { docker { image 'node:12.16.2' } }
    stages {
        stage('test') {
            steps {
                sh 'npm i'
                sh 'npx mocha test/index.js'
            }
        }
    }
}