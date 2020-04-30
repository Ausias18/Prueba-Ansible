pipeline {
  agent any
  
  stages {
	        stage('Debug') {
       steps {
           ansiblePlaybook inventory: winhost -m win_ping
       	      }
     			}
        stage('Configure') {
       steps {
           ansiblePlaybook  inventory: 'inventory.yml', playbook: 'iis-ansible.yml'
       	      }
     			}
         }
	 }
