node('built-in') 
{
    stage('Continuous Download') 
	{
    git 'https://github.com/Manohar-Pittala/Jenkins.git'
	}
    stage('Continuous Build') 
	{
    sh label: '', script: 'mvn package'
	}
    
}
