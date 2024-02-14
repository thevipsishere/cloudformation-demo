pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack \
    --stack-name my-stack-name1 \
    --template-body file://user-group.yaml \
    --capabilities CAPABILITY_NAMED_IAM --region 'ap-south-1'"
              }
             }
            }
            }
