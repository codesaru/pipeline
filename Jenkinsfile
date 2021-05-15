pipeline{
   agent any
   stages{
      stage("compile"){
        steps{ 
          sh "mvn compile"
        }
      }
      stage("unit test"){
        steps{ sh "mvn test" }
      }
   }

}
