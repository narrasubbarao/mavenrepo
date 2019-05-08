node("prod"){
stage("checkout"){
git"https://github.com/narrasubbarao/mavenrepo.git"
}
stage("build"){
def mvnhome = tool name:'MAVEN_HOME', type:'maven'
bat "${mvnhome}\\bin\\mvn package"
}
}
