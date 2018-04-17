node { 
  stage("Clone Repository"){
  checkout scm
  }
  stage("one"){
  sh 'echo Sample > myfile.txt'
        script {
          // trim removes leading and trailing whitespace from the string
          myVar = readFile('myfile.txt').trim()
        }
        echo "${myVar}" // prints 'hotness'
  }
    stage('two') {
      steps {
        echo "${myVar}" // prints 'hotness'
      }
    }

}
