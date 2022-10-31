pipeline{
     agent any
  stages{
stage('Pull') {
        steps {
          script{
            checkout([$class: 'GitSCM', branches: [[name: '*/main']],
               userRemoteConfigs:[[
                credentialsId: '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',
                url: 'https://github.com/SouhaBousselmi/angular.git']]])
                 retry(3) {
          checkout scm
        }
        }
    }
}
  }}
