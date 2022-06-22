node {
    stage('Code Clone') {
		git branch: 'main', url: 'https://github.com/Rameshagwd/Devops.git'
         
    }
	
	stage('MVN Clean') {
		sh 'mvn clean'
         
    }
}