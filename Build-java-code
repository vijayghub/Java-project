node{
    stage ('stage1: build job test2'){
    build 'test2'
}
    stage ('stage2: build job test3'){
        build 'test3'
    }
    
    stage ('stage3: build job test3'){
        build 'test2'
    }
}
