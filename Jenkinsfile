node
{
   checkout scm
 
   stage ('Compile')
   { 
      bat 'mvn compile'    
   }
   stage ('test')
   {
      bat 'mvn test'
   }
   stage ('Package')
   {
      bat 'mvn clean install'
   }
   stage ('Documents')
   {
      bat 'mvn site'
   }
   
   
}  
 







