pipeline{
   agent any
   stages{
      stage("test"){
        steps{ sh "echo hello" }
      }
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
