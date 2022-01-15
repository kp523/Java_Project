node
{
   checkout scm
 
   stage ('Compile')
   { 
      bat 'mvn Compile'    
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
 







