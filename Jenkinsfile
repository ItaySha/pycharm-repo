properties([parameters([string(defaultValue: 'itay', name: 'NAME')]), pipelineTriggers([pollSCM('* * * * *')])])
node {
    stage("one"){
        git branch: 'main', url: 'https://github.com/ItaySha/pycharm-repo.git'
        bat "more 1.txt"
    }
}
