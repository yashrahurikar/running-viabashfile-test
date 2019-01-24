pipeline{
agent any
stage("Testing Stage"){
sh 'source test.sh'
sh '_test_func'
}
stage("Build State"){
sh 'yarn add package.json'
sh 'yarn build'
}
}
