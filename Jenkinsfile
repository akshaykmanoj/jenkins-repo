pipeline {
    agent any

    stages {
        stage('Git Checkout') {
            steps {
                git branch: 'main', credentialsId: 'git-key', url: 'https://github.com/akshaykmanoj/jenkins-repo.git'
            }
        }

        // stage('Build') {
        //     steps {
        //         dir('./Example Hello World Apps/C#/MyApp') {
        //             sh 'dotnet build'
        //         }
        //     }
        // }

        // stage('Unit Test') {
        //     steps {
        //         dir('./Example Hello World Apps/C#/MyApp') {
        //             sh 'dotnet test'
        //         }
        //     }
        // }

        // stage('Code Analysis') {
        //     steps {
        //         withSonarQubeEnv('SonarCloud') {
        //             // Run SonarCloud analysis
        //             sh 'dotnet sonarscanner begin /k:"akshaykmanoj_jenkins-repo" /d:sonar.login="9cd4c30f472e3b2037fa99928a26f0c9181770eb"'
        //             sh 'dotnet build'
        //             sh 'dotnet sonarscanner end /d:sonar.login="9cd4c30f472e3b2037fa99928a26f0c9181770eb"'
        //         }
        //     }
        // }
        

        // Add additional stages for unit tests, code analysis, etc.
    }
}
