pipeline
{ 
    agent any
    stages {
        stage("Execute grafana"){
            steps{
                sh "sudo ansible-playbook /etc/ansible/Install_Prometheus/install_Prometheus.yml"
                
            }            
        }
    }
}
