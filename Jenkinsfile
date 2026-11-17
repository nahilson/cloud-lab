pipeline {
    agent any
    stages {
        stage("Checkout") {
            steps {
                git url: "https://github.com/nahilson/cloud-lab.git", branch:
        }
    }
    stage("Build") {
        steps {
            sh "docker build -t myflask:test ."
        }
    }
}
