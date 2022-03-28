pipeline (
  agent any
  stages {
    stage ( 'Run files' ) {
    parallel {
      stage( 'test windows') {
        steps {
          sh "echo stage"
        }
      }
      stage( 'test on jenkins' ) {
        steps {
          sh "echo stage 2"
        }
      }
    }
    }
  }
