pipeline {
  agent any
  
  stages {
        stage('Configure') {
       steps {
           sh 'pwd'
	   sh 'pip install pywinrm'
	   sh 'ansible-playbook -i inventory.yml iis-ansible.yml -vvv'
       	      }
     			}
         }
	 }
