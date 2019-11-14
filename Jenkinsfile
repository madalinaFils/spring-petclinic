pipeline {
    agent any  // pe ce masina va rula
    stages {
     stage('Build') {
         steps {
            withMaven(maven: 'maven-installation', mavenSettingsConfig: 'maven-settings.xml') {
            bat 'mvn -DskipTests clean package'
             }
       }
}
   
}
