pipeline {
    agent any
    
tools 
{
    maven "M2_HOME"
}


    stages {
         stage('GIT') {
            steps {
               echo 'bdina git tw'

              git branch:'main',url: 'https://github.com/ihebm123/TestMagasin.git'

            }
         }
           stage('CLEAN') {
            steps {
              
          script {
   
               sh "mvn clean"
   
            }
   
        }
             }
             
         
        
    
}
}

