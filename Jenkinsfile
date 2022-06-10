pipeline {
  agent any
  stages {
    stage ("Print variable") {
      steps {
        wrap([$class: "MaskPasswordsBuildWrapper",
              varPasswordPairs: [[password: MY_PASSWORD]]]) {
          echo "Password: ${MY_PASSWORD}"
        }
      }
    }
  }
}
