pipeline {
 agent any
 stages {
 stage('Clone Repository') {
 steps {
 git 'https://github.com/<your-username>/jenkins-nodejs-demo.git'
 }
 }
 stage('Install Dependencies') {
 steps {
 sh 'npm install'
 }
 }
 stage('Run Tests') {
 steps {
 sh 'npm test'
 }
 }
 stage('Build') {
 steps {
 echo 'Build completed successfully'
 }
 }
 }
}
