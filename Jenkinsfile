pipeline {
  agent any
  stages {
    stage('Bash node-v') {
      steps {
        sh 'node -v'
      }
    }

    stage('uTest Scan') {
      steps {
        utesterstartscan(scanSettingsId: 'd7984f4f-2804-41f8-9db0-c56fbe12c141', project: 'Tom', baseAddress: 'https://www.user1st.com')
      }
    }

  }
}