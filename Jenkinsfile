pipeline{
  agent none
  stages{
     stage("Build Master"){
        when{
           tag 'release-*'
        }
         steps{
           echo "Building Tag catched in main"
         }
     }     
    
  }
}
