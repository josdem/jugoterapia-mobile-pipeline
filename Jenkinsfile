#!/usr/bin/env groovy
pipeline {
  agent any
  stages {
    stage('Build Jugoterapia') {
      steps {
        echo 'Building Jugoterapia'
        build job: 'jugoterapia-mobile-debug'
        echo 'Done!'
      }
    }
    stage('Run Jugoterapia smoke test') {
      steps {
        echo 'Running Jugoterapia'
        build job: 'jugoterapia-mobile-debug'
        echo 'Done!'
      }
    }
}
