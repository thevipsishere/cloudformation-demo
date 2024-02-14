pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name user-group --template-body file://user-group.yaml --region 'ap-south-1'"
              }
             }
            }
            }
