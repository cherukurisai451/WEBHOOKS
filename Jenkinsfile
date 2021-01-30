node {
    stage ('SCM CHECKOUT') {
        git 'https://github.com/cherukurisai451/WEBHOOKS.git'
    }
    stage ('BUILD'){
        sh 'mvn clean package'
    }
    stage('test') {
        echo 'TEST'
    }
    stage('deploy'){
        echo 'Deploy'
    }
}
