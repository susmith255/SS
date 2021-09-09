pipeline { 
    agent any 
    options {
        skipStagesAfterUnstable()
    }
    stages {
        stage('Build') { 
            steps { 
                sh 'echo "print"' 
            }
        }
        stage('Test'){
            steps {
                sh 'echo "scan"' 
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "printf"'
            }
        }
    }
}
