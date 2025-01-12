pipeline {
    agent any

    stages {
        stage('install grafana') {
            steps {
               sh "sudo ansible-playbook /role_install.yml"
            }   
        }
    }
}
