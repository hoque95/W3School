pipeline{

agent any

stages{
stage('version'){

steps{
    bat 'mvn -version'
}
}
 stage ('clean')
 steps {
 'mvn clean'
 }
 }
 stage ('install'){
 steps{
 bat 'mvn package'
 }
 }
 }
}

