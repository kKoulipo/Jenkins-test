node {
    stage('clone'){
        checkout scm
    }
    
    stage("run et push"){
        def Image= docker.image("my_nginx")
        Image.withRun(){
            
        }
        Image.push()
    }
}
