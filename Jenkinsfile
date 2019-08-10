pipeline{
    agent none
    stages {
        stage("primer stage") {
            steps {
                script {
                    node {
                        println "My primer stage"
                    }
                }
            }
        }
        stage("segundo stage") {
            steps {
                script {
                    node {
                        println "My segundo stage"
                    }
                }
            }
        }
    }
}
