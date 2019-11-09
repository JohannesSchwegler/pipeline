pipeline {
  agent any
  stages {
    stage('HelloWorld') {
      steps {
        echo 'Hello World'
      }
    }
    
    stage('Compile-Package') {
      steps {
         bat 'mvn package'
      }
    }
    
  }
}
