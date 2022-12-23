pipeline{
        agent {
                label{
				label 'built-in'
                customWorkspace '/mnt/myproject'
               }
       }
       stages {
                stage ('deploy'){
                        steps{
                              sh "rm -rf *"
			      sh "scp -r index.html /var/www/html/
			      sh "chmod -R 777 /var/www/html/index.html
                             }
                }
				
                stage ('start'){
                        steps {
                                sh "service httpd start"
                              }
}					
       }
}
