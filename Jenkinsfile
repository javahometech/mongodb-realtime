pipeline{
    agent any
    stages{
        stage('Git Checkout'){
            steps{
                git url: 'https://github.com/javahometech/mongodb-realtime'
            }
        }
        
        stage('Dev Deploy'){
            steps{
                sh "ansible-playbook -i dev.invenory mongodb.yml"
            }
        }
        
    }
}