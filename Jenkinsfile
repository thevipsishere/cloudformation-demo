pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack \
    --stack-name user-group \
    --template-body file://user-group.yaml \
    --parameters ParameterKey=KeyName,ParameterValue=ddd.pem \
    --capabilities CAPABILITY_NAMED_IAM \
    --region 'ap-south-1'"
              }
             }
            }
            }
