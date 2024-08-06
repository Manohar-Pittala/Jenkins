node('master') 
{
    stage('Continuous Download') 
	{
    git 'https://https://github.com/Manohar-Pittala/maven.git'
	}
    stage('Continuous Build') 
	{
    sh label: '', script: 'mvn package'
	}
    
}
