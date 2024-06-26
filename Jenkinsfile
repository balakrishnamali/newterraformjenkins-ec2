pipeline {
    agent  { label 'agent' }
        stages {
            stage ('Test Pipeline') {
                steps {
                    sh 'echo "This is Jenkins Pipeline"'
                    sh 'sudo apt-get update'
                    sh 'sudo apt-get install -y gnupg software-properties-common'
                }
            }
        }
}
