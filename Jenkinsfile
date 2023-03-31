pipeline {
  
  agent any
  
  environment {
        var1 = "hehe"
        var2   = 'lmaoo'
    }
  
  parameters {
    booleanParam(name: "lmaoo??")
  }
  stages {
    
    stage ('env'){
      steps {
        echo "${var1}"
        echo "${var2}"
        
      }
          
    }
    stage ('build') {
      when {
        expression {
        1 == 1
        }
      }
      steps{
      
//         echo "heheee master  branchhhh!!!"
//         echo "step 22222"
//         echo "33333333333333"
        echo "lmaoo"
        
      }
      
    }
    
  }

}
