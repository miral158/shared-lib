
pipeline {
    agent any
libraries {
  lib('sharedlib@master')
}
    stages {
        stage('demo') {
            steps {
                demo.hello()
            }
        }
    }
}
