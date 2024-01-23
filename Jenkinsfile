pipeline {
    agent any

    
    stages {
        stage('git clone') {
            steps {
                git branch: 'main', url: 'https://github.com/surendratig/payany.git'
            }
        }
         stage('test') {
            steps {
                echo 'test is completed'
            }
        }
       stage('deploy') {
            steps {
                echo 'deployment is completed'
            }
        }
    }
}
