pipeline{
  agent any
  stages{
    stage('checkout'){
      when {
        branch 'deploy'
      }
        steps{
            echo "In deploy branch !!!"    
  }
  
}
     stage('build'){
      when {
        branch 'test'
      }
        steps{
            echo "in test branch"    
  }
  
}
    stage('upload'){
      when {
        branch 'main'
      }
        steps{
            echo "in main branch"    
  }
  
}
  }
}
