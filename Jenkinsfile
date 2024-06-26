pipeline {
    agent  { label 'agent' }
        stages {
            stage ('Test Pipeline') {
                steps {
                    sh 'echo "This is Jenkins Pipeline"'
                    sh 'sudo apt-get update'
                    sh 'sudo apt-get install -y gnupg software-properties-common'
                    sh 'wget -O- https://apt.releases.hashicorp.com/gpg | gpg --dearmor | sudo tee /usr/share/keyrings/hashicorp-archive-keyring.gpg > /dev/null'
                }
            }
        }
}
