pipeline{
  agent any
  
  stages{
    stage("Compile code"){
      steps{
          ba "mvn compile"
       }
    }
     stage("Test code"){
       steps{
          ba "mvn test"
       }
    }
     stage("Build code"){
       steps{
          ba "mvn build"
       }
    }
     stage("Install"){
       steps{
          ba "mvn install"
       }
    }
  }
}

