pipeline 
{
    agent any

    stages 
    {
        stage('Build') 
        {
            steps 
            {
                echo 'Build App'
            }
        }
        stage('Test') 
        {
            steps 
            {
                echo 'Test App'
            }
        }
        stage('Deploy') 
        {
            steps 
            {
                echo 'Deploy App'
            }
        }
    }
    post
    {
    always
    {
    emailext body: 'How are you', subject: 'status', to: 'pejulawson18@gmail.com'

    }

    }
}
