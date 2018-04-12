node { 
  stage "Clone Repository"
  checkout scm
  stage "Parameter Value"
  sh "SampleValue=${env.BUILD_NUMBER}"
  echo SampleValue
  stage "Display Parameter"
  echo SampleValue
}
