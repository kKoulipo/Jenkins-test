node {
    def app
    stage("clone"){
        checkout scm
    }
    
    stage("build"){
        app =docker.build('run/alpine')
    }
    stage('run'){
        docker.image('run/alpine').withRun(){ c ->
            sh 'docker ps'
	    sh 'pwd'
        }

    }
stage("pwd){
sh 'pwd'
}
}
