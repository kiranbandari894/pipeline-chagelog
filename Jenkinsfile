pipeline{
  agent none
  stages{
     stage("Build Master"){
        when{
           changeRequest()
        }
         steps{
           echo "Change log picked successfully"
         }
     }     
    
  }
}
