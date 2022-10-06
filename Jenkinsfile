pipeline{
  agent any  
  stages{  
      stage("Run ansible playbook"){
        steps{
        ansiblePlaybook credentialsId: 'ssh-key', inventory: 'hosts', playbook: 'nginx_install.yaml'
        }
      }

                stage('print nginx is Installed') {
                    steps{
                        sh"echo nginx is installed on all servers"

         }
        }
      
                    stage('deploy to nginx') (
                        steps(
                            sh"echo deploy to nginx"
                      
  }
  
  }
  
  }
      
    }
  

