pipeline{
 agent any
 stages{
    stage {'Build'}{
     echo 'Running build automation'
     sh './gradlew build --no-daemon'
     archiveartifacts artifacts 'dist/trainSchedule.zip'
      }
    }
 }
}
