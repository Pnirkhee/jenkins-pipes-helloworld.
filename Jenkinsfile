node {
       stage('prepare') {
       sh "git clean -fdx"
                        }
    
        stage('test') {
        sh "./test_hello.sh"
                      }
     
        stage('package') {
        sh "tar -cvzf hello.tar.gz hello.sh"
                         }
    
     } 
  
       
