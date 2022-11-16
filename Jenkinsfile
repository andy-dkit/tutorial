pipeline {
    agent any
    stages {
        stage("Test") {
            steps {
                echo "Hello World"
                sh "ls"
                sh "whoami"
            }
        }
        stage("Download Code") {
            steps {
                git branch: 'main', url: 'https://github.com/andy-dkit/tutorial.git'
                sh "cat test1.txt"
            }
        }
    }
}