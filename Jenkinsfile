pipeline {
    agent any
    stages {
      stage('Build') {
            steps {
                    echo 'Building the project';
                    }
            }
      stage('Unit-Test') {
             steps {
                    echo 'Running JUnit Tests';
                    }    
           }
      stage('Quality-Gate') {
             steps {
                    echo 'Verifying Quality Gates';
                    }    
           }
       stage('Deploy') {
             steps {
                    echo 'Deploying';
                    }    
           }
    }
}
