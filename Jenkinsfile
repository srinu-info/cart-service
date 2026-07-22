@Library('jenkins-shared-library') _

def configMap = [
    component: "cart-service"
]

if (env.BRANCH_NAME == "development") {

    javaSharedJenkins(configMap)

}
else if (env.BRANCH_NAME == "main") {

    javaProdJenkins(configMap)

}