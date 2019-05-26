node {
    checkout scm
    /* .. snip .. */
}
pipeline {
    agent any

    tools {nodejs "node"}

    stages {
        stage('Build') {
            steps {
                sh 'npm i'
            }
        }
        stage('Deploy via CodeDeploy'){

        }
    }
}

