pipeline{
    agent any
    stages{
        stage('Run Collection'){
            steps{
            
                docker run -v "%cd%":/etc/newman --workdir /etc/newman -t postman/newman run aegis_collection_ci.json --environment dev_environment.json --disable-unicode
        }
    }
}
}