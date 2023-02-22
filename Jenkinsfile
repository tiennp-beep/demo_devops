// pipeline {
//     agent any
//     stages {
//         stage('Build'){
//             steps {
//                 sh '''
//                 echo 'Install Terraform'
//                 '''
//             }
//         }
//     }
// }
pipeline {
    agent {
        docker { image 'node:16.19.0' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}
