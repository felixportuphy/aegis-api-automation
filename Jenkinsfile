pipeline{
    agent any
    stages{
        stage('Run Collection'){
            steps{
               
                sh 'docker run -v .:/etc/newman --workdir /etc/newman -t postman/newman aegis_collection_ci.json --environment dev_environment.json --disable-unicode'
        }
    }
}
}