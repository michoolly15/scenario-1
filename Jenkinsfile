


pipeline {
    agent any

    stages {
        stage ('Build_angular_app') {
            when {
                changeset "**/angular-app/**"  
            }
            steps {
                echo "Start building angular app if there is any new commit"
                
            }
        }

        stage('Build_react_app') {
            when {
                changeset "**/react-app/**"  
            }
            steps {
                echo "Start building react app if there is any new commit"
                
            }
        }
         stage('Build_vue_app') {
            when {
                changeset "**/vue-app/**"  
            }
            steps {
                echo "Start building angular app if there is any new commit"
                
            }
        }
    }
}
