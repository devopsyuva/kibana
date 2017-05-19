package {
  agent any
  stages {
    stage ('build') {
      steps {
      sh 'cp -r /root/jenkins/workspace/Ansibletest/ /etc/ansible'
      sh 'cd /etc/ansible'
      }
    }
    stage ('test') {
      steps {
      sh 'ansible all -m ping'
      }
    }
  }
}
