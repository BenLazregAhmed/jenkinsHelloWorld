node {
    stage('clone') {
    git 'https://github.com/BenLazregAhmed/jenkinsHelloWorld.git'
}
    stage('build') {
    sh 'javac Main.java'
}
    stage('run') {
    sh 'java Main'
}
}