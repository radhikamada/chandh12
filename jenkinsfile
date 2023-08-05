pipeline {
    agent any
    stages {
        stage ('cloning the code from git URL') {
            steps {
            echo "clone code"
        }
    }
      stage('building the code by using maven') {
          steps {
              echo "builging code "
          }
      }
      stage('testing the code by using unit test cases') {
          steps {
              echo "testing the code using the unit test cases"
          }
      }
      stage ('deploying the code on to the servers ') {
          steps {
              echo "deploying the code on the servers"
          }
      }
      stage ('releasing the code on to the production servers') {
          steps {
              echo "deploying the code on to the production servers"
          }
      }
      stage ('post build notifications to the devteam') {
          steps {
              echo "trigging the mail devteam@gmail.com"
          }
      }
    }
}
