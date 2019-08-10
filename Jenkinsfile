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
            enviroment {
                myUsername = "Angel antezana"
            }
            steps {
                script {
                    node {
                        println "My segundo stage"
                        pirntln "Nombre de usuario $myUsername"
                    }
                }
            }
        }
    }
}
