node{
    
    stage('1st stage git clone java code') {
     git 'https://github.com/maha4iac/mahalogin.git'
    }
    
    
    stage('2st stage execute maven targets') {
     sh label: '', script: 'mvn install'
    }
}
