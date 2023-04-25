node {
    stage('checkout'){
        def scmVars = checkout scm
        scmVars.dump()
    }
    stage('Example') {
        sh "printenv"
    }
}