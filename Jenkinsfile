node {
        stage('clone') {
                git branch: 'main', url: 'https://github.com/MKevin73/repo_jenkins.git'
            }
        stage('build') {
                sh '''javac Main.java'''
            }
        stage('run') {
                sh '''java Main'''
            }
}