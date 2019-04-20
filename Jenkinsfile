node{
stage("checkout"){
git"https://github.com/narrasubbarao/mavenrepo.git"
}
stage("build"){
def mvnhome = tool name: 'MVN_HOME', type: 'maven'
sh "${mvnhome}/bin/mvn package"
}
}
