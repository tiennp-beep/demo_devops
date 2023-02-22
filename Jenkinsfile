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
        docker { image 'nginx' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'cat /usr/share/nginx/www/index.html'
            }
        }
    }
}
