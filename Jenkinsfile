#!/usr/bin/env groovy

pipeline {
    
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sh '. layers/poky/oe-init-build-env build; bitbake update-image'
            }
        }
    }
}


