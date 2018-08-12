#!groovy

library identifier: 'jenkins-pipeline-utils@master', retriever: modernSCM(
        [$class       : 'GitSCMSource',
         remote       : 'git@github.com:beppo/jenkins-pipeline-utils.git',
         credentialsId: 'github'])

node {
	utils.deployToEnvironment()
}

