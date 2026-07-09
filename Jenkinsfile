node {
  stage('cloning maven project')
  {
    git 'https://github.com/2894-vaishu/mavenproject.git'
  }
  stage('Building maven project')
  {
    bat 'mvn package'
  }
}
