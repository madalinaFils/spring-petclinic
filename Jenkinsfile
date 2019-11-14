pipeline {
    agent any  // pe ce masina va rula
    stages {
        stage('Build') {
            withMaven(maven: 'maven-installation', mavenSettingsConfig: 'maven-settings.xml') {
            sh 'mvn test'
        }
            
        }
    }
}
