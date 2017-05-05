pipeline {
  agent none
  stages {
    stage('checkout') {
      steps {
        echo 'tst'
        node(label: 'node1') {
          svn 'svn://ec2-34-248-251-12.eu-west-1.compute.amazonaws.com:8098/ISBA/archibus/webcentral/trunk'
        }
        
      }
    }
  }
}