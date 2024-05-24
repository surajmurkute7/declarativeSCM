pipeline {
    agent any

    stages {
        stage('fetching the code from git hub') {
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

