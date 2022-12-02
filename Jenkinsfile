pipeline{
    agent any
    stages{
        stage('1-EngEkong'){
            steps{
                sh 'ps -ef'
                sh 'sudo systemctl status Jenkins'
            }
        }
        stage('2-EngAnakua'){
            steps{
                sh 'echo this is eng anakue'
            }
        }
        stage('3-EngBett'){
            steps{
                sh 'echo this is eng bett'
            }
        }
        stage('4-EngKeukeu'){
            steps{
                sh 'echo "this is special eng keukeu"'
                sh 'echo "Also known as Eng Ekop"'
            }

                
        }
    }
}