pipeline{
    agent {
        label "jenkins-agent"
    }
    stages{
        stage("building for the dev branch"){
            when{
                branch "main"
            }
            steps{
                sh "docker-compose up -d"
            }
        }
    }
}
