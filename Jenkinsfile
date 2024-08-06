node('built-in') 
{
    stage('Continuous Download') 
	{
    git 'https://github.com/Manohar-Pittala/maven.git'
	}
    stage('Continuous Build') 
	{
    sh label: '', script: 'mvn package'
	}
    
}
