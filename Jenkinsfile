pipeline{
  agent any
  stages{
    stage("Compile code"){
      steps{
          sh "mvn compile"
       }
    }
     stage("Test code"){
       steps{
          sh "mvn test"
       }
    }
     stage("Build code"){
       steps{
          sh "mvn build"
       }
    }
     stage("Install"){
       steps{
          sh "mvn install"
       }
    }
  }
}
