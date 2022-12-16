pipeline {
    agent any
  
      stages {
        stage('deployment') {
            steps {
              script {
                 kubernetesDeploy configs: 'deploy/kubernetes/complete-demo.yaml', kubeconfigId: 'k8-id' 
             }
           }   
        }
    }
}
