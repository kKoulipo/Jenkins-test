node {
    stage("agent"){
        agent {
            dockerfile true
        }
        sh 'pwd'
    }
    stage("clone"){
        checkout scm
    }
    stage("build"){
        docker.build('my_nginx')
    }
    stage("run"){
        docker.image('my_nginx').withRun(){
        
    }
    stage('images list'){
        sh 'docker images'
    }
    
 }
}
