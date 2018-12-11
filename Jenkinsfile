node{
    stage(SCM checkout'){
        git 'https://github.com/Venkatesh-Nittu/my-app'
    }
    stage('Comple-Package'){
        def mhome = tool name: 'maven3', type: 'maven'
        sh "${mhome}/bin/mvn package"
    }
}
