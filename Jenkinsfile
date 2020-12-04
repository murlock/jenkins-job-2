pipeline {
    agent any;
    stages {
        stage('Build') {
            steps {
                copyArtifacts(projectName: '/my-github/jenkins-job-1/master');
                sh '''
                cat magic
                '''
            }
        }
    }
}
