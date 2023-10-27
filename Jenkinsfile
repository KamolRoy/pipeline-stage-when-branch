pipeline{
    agent any
    environment{
        version='2.0'
        name = 'Jeff'
    }

    stages {
        stage('Build'){
            when {
                allOf {
                    expression{
                    version == "1.0"
                    name == 'Jeff'
                    }
                }
            }
            steps{
                echo "${version}"
                echo "${name}"
            }
        }
    }   
}


