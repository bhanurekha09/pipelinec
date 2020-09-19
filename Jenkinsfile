pipeline {

agent none

          stages{
                 stage ( 'STAGE 1'){
                        agent { label 'master' }
                         steps {
                                sh 'git clone https://github.com/bhanurekha09/csource.git'
                                sh 'make'
                                }
                   }
            }
                                
                       
                
}
