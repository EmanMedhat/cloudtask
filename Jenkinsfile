pipeline {
    agent any

    stages {
        stage('Pull Repository') {
            steps {
                git url: 'https://github.com/EmanMedhat/cloudtask.git', branch: 'master'
            }
        }
        stage('Execute Bash Script') {
            steps {
                bat 'dir list_files.sh' // Execute your bash script
            }
        }
    }
}
