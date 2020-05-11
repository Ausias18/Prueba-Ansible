pipeline {
  agent any
  
  stages {
        stage('Configure') {
       steps {
           sh ansible-playbook -i inventory.yml iis-ansible.yml -vvv
       	      }
     			}
         }
	 }
