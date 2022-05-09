pipeline{
    agent any
    stages{
        stage('Run Collection'){
            steps{
                sh 'docker run -v ${WORKSPACE}:/etc/newman --workdir /etc/newman run aegis_collection_ci.json --disable-unicode'
        }
    }
}
}