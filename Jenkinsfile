node {
    stage('Checkout') {
        git 'https://github.com/Cervator/sample-spring-webapp.git'
    }
    stage('Build') {
        sh 'chmod a+x gradlew'
        sh './gradlew build'
    }
}
