pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack \
    --stack-name user-group \
    --template-body file://user-group.yaml \
    --parameters ParameterKey=ddd.pem,ParameterValue=YourKeyName \
    --capabilities CAPABILITY_NAMED_IAM \
    --region 'ap-south-1'"
              }
             }
            }
            }
