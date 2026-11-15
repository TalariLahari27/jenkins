node('s1') {
    stage('Checkout code') {
        checkout scm
    }
    stage('Build project') {
        sh 'echo "Successfully running on slave s1!"'
        sh 'hostname'
    }
}
