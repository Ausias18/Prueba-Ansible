pipeline {
  agent any
  
  stages {
        stage('Configure') {
       steps {
           ansiblePlaybook  inventory: 'inventory.yml', playbook: 'iis-ansible.yml'
       	      }
     			}
         }
	 }
