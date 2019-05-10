pipeline {
agent any
stages{
  stage('Build'){
    steps{
    sh '/home/arnauld/work/env/maven/apache-maven-3.6.1/bin/mvn clean install'
    }
  }
  stage('Test'){
    steps{
    sh '/home/arnauld/work/env/maven/apache-maven-3.6.1/bin/mvn test'
    }
  }
}
}
