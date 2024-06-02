pipeline {
    agent {
        node {
            label "linux && nodejs"
        }
    }
    stages {
        stage("Hello") {
            steps {
                echo("Hello Pipeline")
            }
        }
    }
}