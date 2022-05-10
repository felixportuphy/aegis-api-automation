pipeline{
    agent any
    stages{
        stage('Run Collection'){
            steps{
             sh 'newman run aegis_collection_ci.json -e dev_environment.json'
        }
    }
}
}