node { 
  stage "Clone Repository"
  checkout scm
  stage "Parameter Value"
  sh "SampleValue=${env.BUILD_NUMBER}"
  stage "Display Parameter"
  sh "echo $SampleValue"
}
