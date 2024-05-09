pipeline {
    agent any

    stages {
        stage('Print Hello') {
            steps {
                sh 'echo "Hello, Jenkins!"'
            }
        }
    }
}

// pipeline {
//     agent any
    
//     environment {
//         GITHUB_REPO = 'https://github.com/your/repository.git'
//         FIREBASE_TOKEN = credentials('firebase-token')
//     }
    
//     stages {
//         stage('Checkout') {
//             steps {
//                 // Checkout github repo
//                 git url: "${env.GITHUB_REPO}"
//             }
//         }
        
//         stage('Build') {
//             steps {
//                 // Builds mobile app 
//                 sh 'npm install'
//                 sh 'npm run build'
//             }
//         }
        
//         stage('Test') {
//             steps {
//                 // Run test
//                 sh 'npm test'
//             }
//         }
        
//         stage('Deploy') {
//             steps {
//                 // Deploy the app (replace with your deployment commands)
//                 // For example, deploying to Firebase
//                 sh "firebase deploy --token '${env.FIREBASE_TOKEN}'"
//             }
//         }
//     }
// }
