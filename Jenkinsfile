pipeline { 
  
   agent any

   stages {
   
     stage('Compile') { 
        steps { 
           sh 'echo "compiling application"'
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'echo "testing application"'
        }
      }

         stage('Deploy') { 
         steps { 
           sh 'echo "deploying application"'
         }

     }
  
   	}

   }