pipeline {
    agent any
    
    stages{
        stage('build') {
            environment{
                SOME_USER_PASSWORD = credentials('some_username_password')
                SOME_SECRET = credentials('some_secret')
                }
       steps {
                echo "some_username_password ${SOME_USER_PASSWORD}"
                }
                }
                
}
}
