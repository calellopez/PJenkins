pipeline {
  agent any
  stages {
    stage('build assets') {
      steps {
        dir(path: 'sell script') {
          sh '''pipeline {
    agent any
    stages {
        stage(\'Build\') {
            steps {
                sh \'echo "Hello World"\'
                sh \'\'\'
                    echo "Multiline shell steps works too"
                    ls -lah
                \'\'\'
            }
        }
    }
}'''
          }

        }
      }
    }
  }