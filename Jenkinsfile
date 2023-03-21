
pipeline {
    agent any
    /*environment {
        version = "1.0"
    }*/
    stages {
        stage('Example Build') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Example Deploy') {
            when {
                expression { BRANCH_NAME ==~ /(production|staging)/ }
                // version == "1.0"
            }
            steps {
                echo 'Deploying'
            }
        }
    }
}
