pipeline { 
    agent any  
    stages { 
        stage('sample1') {
          steps {
            echo 'summition'
          }
        }
        stage('sample 2') { 
            steps { 
               echo 'addition...' 
               sh 'python3 ritvik.py'
              //bat 'mvn package'
            }
        }
   
}
    }
