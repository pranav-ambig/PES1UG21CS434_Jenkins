pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                script {
                    // Compile the .cpp file using a shell script
                    sh 'sh compile_script.sh PES1UG21CS434-1.cpp'
                }
            }
        }

        stage('Test') {
            steps {
                script {
                    // Print the output of the compiled .cpp file using a shell script
                    sh 'sh test_script.sh PES1UG21CS434-1'
                }
            }
        }
    }
}
