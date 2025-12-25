pipeline {  
    agent any{
        parameters {
            choice choices: ['master', 'dev', 'qa'], description: 'select environment', name: 'branchname'
        }
        stages {  
       	    stage("git_checkout") {  
           	    steps {  
              	    echo "cloning repository" 
              	    echo "repo cloned successfully"  
              	    }
         	    } 
        }
}
