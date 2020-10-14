pipeline {
    agent any
    stages {
        stage('Clone') {
            parallel {
                stage('svn') {
                    steps {
                        echo "chrome tests"
                    }
                }
                stage('Firefox') {
                    steps {
                        echo "Firefox Tests"
                    }
                }
                stage('Internet Explorer') {
                    steps {
                        echo "Internet Explorer Tests"
                    }
                }
            }
        }
    }
}
