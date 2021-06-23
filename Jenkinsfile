node {
    stage('Clone') {
    git 'https://github.com/priximmo/jenkins-helloworld.git'
    }
    stage('Build') {
    bat 'javac Main.java'
    }
    stage('Run') {
    bat 'java Main'
    }
}