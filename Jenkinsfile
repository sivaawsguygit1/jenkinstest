pipeline {
    agent any
    stages {
        stage('Example Deploy') {
            when {
                //buildingTag()
                branch 'release/*'
                // tag "release-*"
                //tag pattern: "v\\d{1,2}\\.\\d{1,2}\\.\\d{1,2}", comparator: "REGEXP" //v1.2.3
            }
            steps {
                echo 'Building a release bracnch'
            }
        }
        //fdf
    }
}
