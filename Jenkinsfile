node
{
stage("build")
{
echo "${BUILD_NUMBER}"
}
stage("run")
{
sh label: '', script: '1.sh'
}
stage("Test")
{
sh label: '', script: '2.sh'
}
}
