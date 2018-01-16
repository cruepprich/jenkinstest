pipeline {
    agent any
    properties([
        parameters([
            string(name: 'USERNAME'
                ,defaultValue: 'jcat'
                ,description: 'Username', 
            )
            ,string(name: 'PASSWORD'
                ,defaultValue: 'jcat'
                ,description: 'Password', 
            )
        ])
    ])
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                echo 'Username: ${USERNAME}'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
