pipeline{
    agent none;
    
    environment {
        myUsername = "Angel antezana"
        }
    
    stages {

        
        stage("primer stage") {
            steps {
                script {
                    node {
                        println "My primerrr stage jenkinsfile"
                        echo "Nombre de usuariossssss ${myUsername}"
                    }
                }
            }
        }
        stage("segundo stage") {
            environment {
                myUsername = "Angel antezana"
            }
            steps {
                script {
                    node {
                        println "My segundo stage"
                        println "Nombreeeeee de usuario $myUsername"
                    }
                }
            }
        }
    }
}
