pipeline {
        agent { label 'flask' }
        stages {
                stage('update flask') {
                        steps {
                                sh '''
                                sudo apt install -y python3
                                sudo apt install python3-pip -y
                                sudo pip install flask
                                flask run --host=3.82.26.203 --port=5000
                                '''
                        }
                }
        }
}
