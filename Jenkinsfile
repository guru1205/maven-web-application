node{
stage('Git CheckoutSCM'){
git 'https://github.com/guru1205/maven-web-application'
}
stage('Compile-package'){
sh 'mvn clean package'
}
}
