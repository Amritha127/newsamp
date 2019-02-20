pipeline {
agent any
stages {
stage ('build') {
  echo 'build successful'
}
stage ('test: integration-&-quality') {
  echo 'test1 successful'
}
stage ('test: functional') {
  echo 'test2 successful'
}
stage ('test: load-&-security') {
    echo 'test3 successful'  
}
stage ('approval') {
    echo 'approval successful' 
}
stage ('deploy:prod') {
    echo 'deployment successful' 
}
}
}
