//helloooooooooo
//asdfghjkl;'
//dafghjsksls
//aqedrftgjikk1234567890-=-09876543212345-1111111sdfbnjiknbgf
pipeline {
    agent any

    triggers {
        githubPush()
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building the project...'
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the project...'
            }
        }
    }
}
/*pipeline {
    agent any

    triggers {
        githubPush()   // IMPORTANT – this listens to GitHub webhook
    }

    stages {
        stage('Clone Repo') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/Rudransh007x/jen.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building project...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }
    }
}
*/
