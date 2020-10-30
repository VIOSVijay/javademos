pipeline {
  agent any
  stages {
    stage('Build Step') {
      steps {
        sh 'mvn -f javademos/javademos-master/ssgsems/pom.xml -B -DskipTests clean package'
      }
    }

  }
}