pipeline{
    agent {
        label 'slave'
    }
    stages{
        stage('Print server hostname'){
            steps{
                sh 'hostname'
            }
        }
        stage('Server uptime'){
            steps{
                sh 'uptime'
            }
        }
        stage('CPU details'){
            steps{
                sh 'lscpu'
            }
        }
        stage('Memory usage'){
            steps{
                sh 'free -h'
            }
        }
    }
}
