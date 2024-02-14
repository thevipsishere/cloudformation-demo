pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack \
    --stack-name aws-services \
    --template-body file://aws-resources.yaml \
    --capabilities CAPABILITY_NAMED_IAM --region 'ap-south-1'"
              }
             }
            }
            }
