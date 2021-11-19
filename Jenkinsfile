pipeline {
    agent any
    parameters {
        gitParameter branchFilter: '.*', defaultValue: 'main', name: 'SOURCE_BRANCH', type: 'PT_BRANCH'
    }
    stages {
        stage('PRINT NODE') {
            steps {
                script {
                    sh "echo ${env.BRANCH_NAME}"
                }
            }
        } // END OF STAGE PRINT NODE
    } // END OF STAGES
} // END OF PIPELINE