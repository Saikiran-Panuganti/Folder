pipeline{
    agent any
    stages{
        stage("Git Checkingout with private repo"){
            steps{
                echo "This is my first Git checkout from github"
                git branch: 'main', url: 'https://github.com/Saikiran-Panuganti/Folder.git'
            }
        }
    }
}
