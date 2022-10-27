stage('Pull') {
        agent any
        steps {
            checkout([$class: 'GitSCM', branches: [[name: '*/main']]
                credentialsId: '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',
                url: 'https://github.com/SouhaBousselmi/angular.git']

            sh "ls -lat"
        }
    }
