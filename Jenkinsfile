pipeline {
    agent any
    
    stages {
        
        stage('Build') {
            steps {
                // Ensure you're using python3 explicitly
                sh 'python3 -m py_compile sources/add2vals.py sources/test_calc.py sources/app.py sources/calc.py'
            }
        }
    }
}
