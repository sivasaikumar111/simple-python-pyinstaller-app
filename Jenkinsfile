pipeline {
    agent any
    
    stages {
        stage('Checkout SCM') {
            steps {
                checkout scm
            }
        }
        
        stage('Build') {
            steps {
                // Ensure you're using python3 explicitly
                sh 'python3 -m py_compile sources/add2vals.py sources/calc.py'
            }
        }
        
        stage('Test') {
            steps {
                // Your test steps here
            }
        }
    }
}
