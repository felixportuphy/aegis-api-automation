pipeline{
    agent any
    stages{
        stage('Run Collection'){
            steps{
                sh 'npm install -g newman'
                sh 'newman run aegis_collection_ci.json --environment dev_environment.json --disable-unicode'
                // sh 'docker run -v .:/etc/newman --workdir /etc/newman -t postman/newman aegis_collection_ci.json --environment dev_environment.json --disable-unicode'
        }
    }
}
}