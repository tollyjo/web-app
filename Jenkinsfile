node{
  stage('Cloning'){
    sh 'echo Cloning from GitHub'
    sh 'echo Cloning done'
  }
  stage('Building'){
    sh "echo packaging our artifact"
    sh "echo Packing done"
  }
  stage('Testing'){
    sh 'echo Testing with Sonarqube'
    sh 'echo Testing done'
  }
  stage('Deploying'){
    sh 'echo Deploying to nexus'
    sh 'echo Deploying done'
  }
  stage('Tomcat'){
    sh 'echo Pushing to Tomcat'
    sh 'echo Done'
  }
}
