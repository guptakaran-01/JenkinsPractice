pipeline{
    agent any 

    stages{
            stage("build"){
                steps{
                    echo"inside build service -------"
                    sh'javac *.java'
                }
            }
            stage("run--ing"){
                steps{
                    echo" Inside runing service ------"
                    sh'java UserService'
                }
            }


    }
}