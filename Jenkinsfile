@Library('jenkins-shared-library') _

def configMap = [
    project : "roboshop",
    component: "cart"
]

if( ! env.BRANCH_NAME.equalsIgnoreCase('main') ){ 
    nodeJSEKSPipeline(configMap)
}
else{
    echo "Please proceed with PROD process"
}