pipeline{
agent any
stages{
stage('build'){
steps{
 sh 'javac file1.java'
 sh 'javac file2.java'
}
}
stage('run'){
steps{
 sh 'java file1'
 sh 'java file2'
}
}
}
}

