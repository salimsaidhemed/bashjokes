pipeline {
    agent any
    stages {
        stage("build") {
            steps {
                echo "Build Application"
            }
        }
        stage("test") {
            steps {
                echo "Test Application"
            }
        }
        stage("deploy") {
            steps {
                echo "Deploy Application"
                sh './fetchJokes.sh'
            }
        }
    }
}