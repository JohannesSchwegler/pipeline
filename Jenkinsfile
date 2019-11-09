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
         sh 'mvn package'
      }
    }
    
  }
}
