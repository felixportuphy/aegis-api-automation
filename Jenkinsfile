pipeline{
    agent any
    stages{
        stage('Run Collection'){
            steps{
             sh 'cd C:/Users/dell/aegis-api-automation && newman run aegis_collection_ci.json -e dev_environment.json'
        }
    }
}
}