 pipeline {
  agent any
    stages {
        stage('Pull') {
             steps{
                script{
                    checkout([$class: 'GitSCM', branches: [[name: '*/master']],
                        userRemoteConfigs: [[
                            credentialsId: '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',
                            url: 'https://github.com/SouhaBousselmi/angular.git']]])
                }
            }
        }
    }
 }
