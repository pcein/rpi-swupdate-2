#!/usr/bin/env groovy

pipeline {
    
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sh 'source layers/poky/oe-init-build-env; bitbake update-image'
            }
        }
    }
}


