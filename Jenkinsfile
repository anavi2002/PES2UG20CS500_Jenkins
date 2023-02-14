
B.S Anavi <anavi.20029@gmail.com>
10:24 AM (0 minutes ago)
to me

pipeline {
agent any
stages {
stage('Build') {
steps {
sh 'g++ -o PES2UG20CS500-1 try.cpp'
echo "Build Successful
}
}
stage('Test') {
steps {
sh './PES2UG20CS466-1'
}
}
}
post {
always {
echo 'Pipeline completed'
}
failure {
echo 'Pipeline failed'
}
}
}
