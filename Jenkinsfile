node
{

stage('SCM')
{git 'https://github.com/venki090790/maven-samples.git'}


stage('BUILD')
sh label: '', script: 'mvn package'

stage('ARTIFACT')
{archiveArtifacts 'single-module/target/*.jar'}


}