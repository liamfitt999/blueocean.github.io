pipeline {
     agent any
     stages {
        stage('Test'){
            steps {
                sh 'make check'
                junit 'reports/**/*.xml' 
            }
        }
       
     }
}

