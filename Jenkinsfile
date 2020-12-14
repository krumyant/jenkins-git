pipeline {
    agent any
    stages {
        stage('Stage 1') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Wab dab dub la la dub dub test"
                    ls -lah
                    pwd -P
                '''
            }
        }
        stage('Stage 2'){
            steps{
                sh 'echo "Another Stage"'
                sh 'echo "Aloha!"'
            }
        }
    }
}
