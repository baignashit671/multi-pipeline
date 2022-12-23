pipeline{
        agent {
                label{
				label 'built-in'
                customWorkspace '/mnt/myproject'
               }
       }
       stages {
                stage ('stage-1'){
                        steps{
                              sh "mkdir test1"
                             }
                }
				
                stage ('stage-2'){
                        steps {
                                sh "mkdir folder1"
                              }
}					
       }
}
