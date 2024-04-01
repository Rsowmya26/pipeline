pipeline {
    agent any
 
    stages {
        stage('Build') {
            steps {
                // Add steps to build your code if necessary
            }
        }
        stage('Test') {
            steps {
                // Add steps to run tests if necessary
            }
        }
        stage('Binary Search') {
            steps {
                script {
                    def arr = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
                    def target = 7
                    def result = binary_search(arr, target)
                    echo "Target $target found at index $result"
                }
            }
        }
    }
}
