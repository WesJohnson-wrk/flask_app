pipeline {
  agent { label 'flask[' }
  stages {
    stage('update flask') {
      steps {
        sh '''
             sudo apt install -y python3
             sudo apt install python3-pip -y
             sudo pip install flask
             flask run
         '''
      }
   }
  }
}
