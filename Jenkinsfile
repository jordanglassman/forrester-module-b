node {
    stage('checkout') {
        git url: 'https://github.com/jordanglassman/forrester-module-b.git'
    }
    stage('build') {
        withMaven(maven: 'Maven350') {
            sh "mvn clean package"
        }
    }
}
