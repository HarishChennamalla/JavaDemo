pipeline
{
    agent any
    tools
    {
        maven 'MAVEN'
    }
    stages
    {
        stages('Welcome')
        {
            steps
            {
                sh '''
                echo Welcome to multi branch pipeline
                '''
            }
        }    
        stage('Build')
        {
            steps
            {
                sh ' mvn clean package'
            }
        }

    }
}