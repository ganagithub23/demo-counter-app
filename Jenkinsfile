pipeline{

    agent any

    stages {

        stage('Git Checkout'){

            steps{

                script{
                   
                    git branch: 'main', url: 'https://github.com/ganagithub23/demo-counter-app.git'
                }
            }
        }
 
    stage('unit-test'){

            steps{

                script{
                   
                    sh 'mvn test'
                }
            }
        }
    }
}