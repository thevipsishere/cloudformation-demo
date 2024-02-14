pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
                sh """aws cloudformation create-stack \
  --stack-name aws-services \
  --template-body file://path/to/aws-resources.yml \
  --capabilities CAPABILITY_NAMED_IAM \
  --region 'ap-south-1' \
  --parameters ParameterKey=KeyName,ParameterValue=ddd.pem"""
            }
        }
    }
}
