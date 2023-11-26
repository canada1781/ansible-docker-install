pipeline {
    agent { label 'slave' }
    stages {
        stage('Install Docker using ansible playbook') {
            steps {
                script {
                    sh '''
                        ansible-playbook docker_install.yml
                    '''
                }
            }
        }
    }
}


