properties([[$class: 'JobLocalConfiguration', changeReasonComment: ''], pipelineTriggers([pollSCM('* * * * *')])])
node{
    stage("clone"){
        git "https://github.com/menchos11/devops3007.git"
    }
    stage("show files"){
        bat "dir"
    }
}