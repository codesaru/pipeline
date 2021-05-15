pipeline{
   agent any
   tools{ maven 'my_maven' }
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
