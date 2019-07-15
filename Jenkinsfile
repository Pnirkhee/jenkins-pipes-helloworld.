node {
       stage('prepare') {
       sh "git clean -fd"
                        }
    
        stage('test') {
        sh "/var/lib/jenkins/workspace/Migration/jenkins-pipes-helloworld./test_hello.sh"
                      }
     
        stage('package') {
        sh "tar -cvzf hello.tar.gz hello.sh"
                         }
    
     } 
  
       
