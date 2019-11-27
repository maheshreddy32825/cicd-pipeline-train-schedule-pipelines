pipeline{
  agent any
  stages {
     stage ('Build') {
       steps {
         echo 'Running build automation'
         sh './gradlew build --no-daemon'
         archiveArtifatcs artifacts: 'dist/trainSchedule.zip'
        }
      }
   }
}
