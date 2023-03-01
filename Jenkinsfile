pipeline {
        agent any
        stages {
            stages ('Git-Checkout') {
                steps {
                        echo "Checking out from Git Repo";
                        git 'https://github.com/NilamSingh21/PipelineScript.git'
                      }
                  }
        
        stage('Build') {
            steps {
                    echo "Running the checked-out project !";
                  }
                }
        
        stage('Test') {
            steps {
                echo "Running Unit Tests";
                   }
                }
        
        stage('Quality') {
            steps {
                echo "Verifying Quality Gates";
                  }
                }
        
        stage('Deploy') {
            steps {
                echo "Deploying to stage environment for test !";
                   }
              }
        }
}
