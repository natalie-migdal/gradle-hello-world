node('slave'){
  stage('Checkout'){
    checkout scm
  }
  stage('Build Gradle'){
    def gdlHome=tool 'gradle4'
    sh "${gdlHome}/bin/gradle build"    
  }  
}
