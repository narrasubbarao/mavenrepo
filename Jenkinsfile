node("production"){
stage("checkout"){
git"https://github.com/narrasubbarao/mavenrepo.git"
}
stage("build"){
def mvnhome = tool name: 'apache-maven-3.5.0', type: 'maven'
sh "${mvnhome}/bin/mvn package"
}
}
