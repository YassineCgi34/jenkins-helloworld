node {
    stage('clone') {
        git branch: 'main', credentialsId: 'GitHub_ID', url: 'https://github.com/YassineCgi34/jenkins-helloworld.git'
    }
    stage('build') {
        sh 'javac Main.java'
    }
    stage('run') {
        sh 'java Main'
    }
}
