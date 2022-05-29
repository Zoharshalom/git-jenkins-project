properties([pipelineTriggers([pollSCM('* * * * *')])])
node {
    stage('clone'){
        git "https://github.com/Zoharshalom/git-jenkins-project.git"
    }
    stage('show files'){
        bat "dir"
    }
        
}
