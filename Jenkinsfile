pipeline{
    agent any
    stages{
        stage("build"){
            steps{
                bat "mvn clean"
                bat "mvn install"
            }
        }
        stage("test"){
            steps{
                bat "mvn test"
            }
        }
        
    }
}
