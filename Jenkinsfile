pipeline {
 agent any
 parameters {
   choice(
     name: 'Env',
     choices: ['DEV', 'QA', 'UAT', 'PROD'],
     description: 'Passing the Environment'
   )
 }
 stages {
   stage('Environment') {
     steps {
       echo " The environment is ${params.Env}"
     }
   }
   
 }
}
