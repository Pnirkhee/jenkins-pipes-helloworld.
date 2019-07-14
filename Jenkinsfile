node {
     //  stage('prepare') {
      // sh "git clean -fd"
        //                }
    
        stage('test') {
        sh "./test_hello.sh"
                      }
     
        stage('package') {
        sh "tar -cvzf hello.tar.gz hello.sh"
                         }
    
     } 
  
       
