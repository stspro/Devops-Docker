//import hudson.model.*
//import hudson.EnvVars
//import groovy.json.JsonSlurperClassic
//import groovy.json.JsonBuilder
//import groovy.json.JsonOutput
//import java.net.URL

node {
    
   stage '1'
   echo 'checkout'

   git url: "https://github.com/stspro/jenkins2.git"
   
    bat "dir *.*/s"
    catchError {
        bat  'might fail'
    }
    
    echo $readfile C:/DevOps/java_workspace/jenkins2/
        bat "sleep :2"
   
    
     step([$class: 'Mailer', recipients: 'adminsomewhere@abc.com'])
    
 // bat 'git rev-parse HEAD > GIT_COMMIT'
   //def shortCommit = readFile('GIT_COMMIT').take(6)

   stage '2'
   echo 'branch'
}
