node{
    
    stage('git clone java code') {
     git 'https://github.com/maha4iac/mahalogin.git'
    }
    
    
    stage('execute maven targets') {
     sh label: '', script: 'mvn install'
    }
}
