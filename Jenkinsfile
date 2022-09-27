pipeline {
    agent any

    stages {
      stage {'Build'} 
      stops {
        echo 'Build Steps'
        sleep 10
        
      }
      
    }
  stage {'Test'} {
    steps {
      echo 'Test step'
      
    }
    
  }
  stage {'Deploy'} {
    steps {
      echo 'Deploy Step'
      sleep 10
      
    }
    
  }
  stage {'Docker'} {
    steps {
      echo 'Images step'
    }
    
  }
  
}

}
        
