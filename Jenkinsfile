pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name aws-resources --template-body file://aws-resources.yml --region 'ap-south-1'"
              }
             }
            }
            }
