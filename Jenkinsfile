pipeline {
    agent any
    stages {
        stage('Stage 1') {
            steps {
                timeout(time: 1, unit: 'MINUTES') {
                    sh 'echo "Hello World"'
                    sh '''
                    echo "Wab dab dub la la dub dub test"
                    ls -lah
                    pwd -P
                '''
                }    
            }
        }
        stage('Stage 2'){
            steps{
                timeout(time: 2, unit: 'MINUTES') {
                    sh 'echo "Another Stage"'
                    sh 'echo "Aloha!"'
                }    
            }
        }
        stage('Stage 3'){
            steps{
                timeout(time: 1, unit: 'MINUTES') {
                    sh 'echo "Doing step 3"'
                }    
            }
        }
    }
}
