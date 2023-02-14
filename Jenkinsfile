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
        docker { image 'node:19.6.0' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}
