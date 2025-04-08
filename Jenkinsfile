node {
    stage('Clone') {
   git 'https://github.com/pepitadalmeida/Jenkins_Helloworld.git' 
}
stage('Build') {
   sh label: '', script: 'javac Main.java' 
}
stage('Run') {
 sh label: '', script: 'java Main'
}
}
