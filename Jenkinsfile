node('slave1'){
  stage('Checkout'){
    checkout scm
  }
  stage('Build Gradle'){
    def gdlHome=tool 'gradle4'
    sh "${gdlHome}/bin/gradle build"    
  }  
}
