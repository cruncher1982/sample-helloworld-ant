// Declarative //
pipeline {
agent any
stages {
stage('Build') {
steps {
sh 'ant build'
}
}
}
}

// Script //
node {
stage('Build') {
sh 'ant build'
}
}
