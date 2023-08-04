@Library('mylib')_

pipeline
{
    agent any
    stages
    {
        stage('contDownload_Loan')
        {
            steps
            {
                script
                {
                    cicd.gitDownload("maven")
                }
            }
        }
        stage('contBuild_Loan')
        {
            steps
            {
                script
                {
                    cicd.mavenBuild()
                }
            }
        }
    }
}

