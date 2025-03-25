pipeline {
    agent any
    tools {
        nodejs 'NodeJS_LTS'  // Nazwa narzędzia z Global Tool Configuration
    }
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                sh 'pwd'
                // sh 'npm i'
                // sh 'composer i'
            }
        }
         stage('Install Dependencies') {
            steps {
                sh 'npm install'  // Wykonanie npm install
            }
        }
    }
}
