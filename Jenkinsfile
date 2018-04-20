#!/usr/bin/env groovy

pipeline {
    
    agent any

    stages {
        stage('Build') {
            steps {
                sh "#!/bin/bash \n" +
		   "./bake"
            }
        }
    }
}


