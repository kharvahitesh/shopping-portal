pipeline{

    agent any

// uncomment the following lines by removing /* and */ to enable
tools{
       nodejs 'nodejs' 
    }
 

    stages{
        stage('compile-app'){
            steps{
                echo 'this is the compile job'
                sh 'npm install'
            }
        }
        stage('test-app'){
            steps{
                echo 'this is the test job'
                sh 'npm test'
 
            }
        }
        stage('package-app'){
            steps{
                echo 'this is the third job'
                sh 'nmp run package'
                sleep 7
            }
        }
    }
    
    post{
        always{
            echo 'this pipeline has completed...'
        }
        
    }
    
pipeline{

    agent any

// uncomment the following lines by removing /* and */ to enable
tools{
       nodejs 'nodejs' 
    }
   

    stages{
        stage('compile-app'){
            steps{
                echo 'this is the compile job'
                sh 'npm install'
       
            }
        }
        stage('test-app'){
            steps{
                echo 'this is the test job'
                sh 'npm test'

            }
        }
        stage('package-app'){
            steps{
                echo 'this is the package job'
                sh 'npm run package'
 
            }
        }
    }
    
    post{
        always{
            echo 'hey, this is my first pipelineas code...'
        }
        
    }
    
pipeline{

    agent any

// uncomment the following lines by removing /* and */ to enable
tools{
       nodejs 'nodesjs' 
    }
 

    stages{
        stage('compile-app'){
            steps{
                echo 'this is the compile job'
                sh 'npm install'
                sleep 4
            }
        }
        stage('test-app'){
            steps{
                echo 'this is the test job'
                sh 'npm test'
                sleep 9
            }
        }
        stage('package-app'){
            steps{
                echo 'this is the package job'
                sh 'npm run package'
                sleep 7
            }
        }
    }
    
    post{
        always{
            echo 'this pipeline has completed...'
        }
        
    }
    
}}}
