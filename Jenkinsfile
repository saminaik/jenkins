 pipeline { agent any stages {
stage('Clone Git') { steps {
git 'https://github.com/BThangaraju/Jenkins.git' }
stage('Test Code') { steps {
sh "chmod u+x Test.py"
}
stage('Build Code') {
steps {
sh "chmod u+x Prog1.py" sh "./Prog1.py"
} 
}
sh "./Test.py" }

}
}

}

