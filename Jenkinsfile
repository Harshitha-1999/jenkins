pipeline{
agent any
stages{
stage('build'){
 steps{
 sh 'mvn install'
 sh 'mvn -B -DskipTests clean package'
}
}
}
}
