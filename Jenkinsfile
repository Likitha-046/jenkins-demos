pipeline {
  agent any

  stages {

    stage('clone') {
      steps {
        git url: 'https://github.com/Likitha-046/jenkins-demos.git',branch: 'main'

      }
    }

    stage('Run Script') {
      steps {
        sh 'chmod +x script.sh'
        sh './script.sh'
      }
    }
  }
}
    
