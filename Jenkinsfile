pipeline{
    agent none;
    
    enviroment {
        myUsername = "Angel antezana"
        }
    
    stages {

        
        stage("primer stage") {
            steps {
                script {
                    node {
                        println "My primer stage"
                        echo "Nombre de usuario ${myUsername}"
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
