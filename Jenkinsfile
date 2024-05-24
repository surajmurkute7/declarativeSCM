pipeline {
    agent any

    stages {
        stage('Fetching the code') {
            steps {
                git branch: 'main', url: 'https://github.com/surajmurkute7/maven_Project.git'
            }
           
        }
        
        stage('build') {
            steps {
                build 'maven-job'
            }
           
        }
       
    }
}

