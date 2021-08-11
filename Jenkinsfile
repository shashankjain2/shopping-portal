pipeline{

    agent any

// uncomment the following lines by removing /* and */ to enable
    tools{
       nodejs 'nodejs' 
    }
    

    stages{
        stage('build'){
            steps{
                echo 'this is the build job'
                sh 'npm install'
            }
        }
        stage('test'){
            steps{
                echo 'this is the test job'
<<<<<<< HEAD
                sh 'npm test'
=======
                sh ‘npm test’
>>>>>>> dbdd86dd49a84518e476a1f8ad18279fdcc578b5
            }
        }
        stage('package'){
            steps{
                echo 'this is the package job'
                sh 'npm run package'
            }
        }
    }
    
    post{
        always{
            echo 'this pipeline has completed...'
        }
        
    }
    
}
