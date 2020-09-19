pipeline {

agent none

          stages{
                 stage ( 'STAGE 1'){
                        agent { label 'master' }
                         steps {
                                sh 'git clone https://github.com/bhanurekha09/csource.git'
                                sh 'pwd'
                                sh  'cd /var/lib/jenkins/workspace/pipeline-18-20'

                                   
                                   sh 'make'
                                }
                   }
            }
                                
                       
                
}
