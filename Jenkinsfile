pipeline {
  agent any
  stages {
    stage('Checkout') { steps { git url: 'https://github.com/sarrabousnina/timesheetproject.git', branch: 'main' } }
    stage('Maven')    { steps { sh 'mvn -v' } }
  }
}