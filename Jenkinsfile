pipeline {
  agent any
  stages {
    stage('HelloWorld') {
      steps {
        echo 'Hello World'
      }
    }
    stage('git clone') {
      steps {
        git clone "https://github.com/JohannesSchwegler/pipeline"
      }
    }
  }
}
