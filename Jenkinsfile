@Library('jenkins-shared-library') _

def configMap = [
    project: "robomart", 
    component: "fronte"

]

if ( !env.BRANCH_NAME.equalsIgnoreCase("main") ) {
    echo "Deploying on non-prod branch"
    javaEKSpipeline(configMap)

} else {
    echo "Kindly follow the CR process"
}