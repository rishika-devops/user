#!groovy
@Library('roboshop-shared-library')_
def configMap = [
    application : "nodejsVM" ,
    component : "user"
]
if(! env.BRANCH_NAME.equalsIgnoreCase('master')){
    pipelineDecision.decidepipeline(configMap)
}
else{
    echo "this is production, deal with cr process"
}