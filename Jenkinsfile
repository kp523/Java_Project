node
{
   checkout scm
 
   stage ('Package')
   { 
      bat 'mvn clean package'    
   }
   stage ('site12')
   {
   bat 'mvn install'
   }
   stage ('Deploy')
     bat 'mvn deploy'
  }
   
}  
 







