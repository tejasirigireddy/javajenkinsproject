pipeline{
  agent any
  stages{
    stage("build")
    {
      steps{
        sh 'mvn clean package'
      }
    }
    stage("getting code from github")
    {
      steps{
        git "https://github.com/tejasirigireddy/javajenkinsproject.git"
        }
      }
    }
  }
