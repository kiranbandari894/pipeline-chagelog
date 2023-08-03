pipeline{
  agent none
  stages{
     stage("Build Master"){
        when{
           changelog '.*some_text.*'
        }
         steps{
           echo "Change log picked successfully"
         }
     }     
    
  }
}
