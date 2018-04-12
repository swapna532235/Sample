node { 
  stage("Clone Repository"){
  checkout scm
  }
  stage("Parameter Value")
  {
    sh "${env.BUILD_NUMBER} > file.txt"
    script{
      myVar = readFile('file.txt').trim()      
    }
    echo ${myvar}
  }
  stage("Display Parameter")
  {
     echo ${myvar}
  }
}
