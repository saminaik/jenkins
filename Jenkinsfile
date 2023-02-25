 pipeline { agent any stages { stage('Clone Git') { /*you can also specify git location */ steps {
  
  git 'https://github.com/saminaik/jenkins.git' } } stage('Build Code') 
                              { steps { sh "chmod u+x Prog1.py" sh "python3 Prog1.py" } } 
                              stage('Test Code') { steps { sh "chmod u+x Test.py" sh "python3 Test.py" } } } }  
