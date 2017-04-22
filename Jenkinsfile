node {
   echo 'Hello World'
   stage('Git') {
       checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/borenXue/tools_sass.git']]])
       sh 'ls'
   }
   stage('Test') {
       echo 'Test stage ....'
   }
   stage('Build') {
       echo 'Build stage ....'
   }
   stage('Upload') {
       echo 'Upload stage ....'
   }
}