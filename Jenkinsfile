pipeline {
  agent any
  stages {
    stage('PIPELINE2') {
      steps {
        sleep(unit: 'MINUTES', time: 2)
        build(job: 'JOB3', propagate: true)
      }
    }

  }
}