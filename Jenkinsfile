node('master') 
{
    stage('CD-s1-master') 
    {
    git 'https://github.com/BABJI-AWS-DEVOPS/MAVN-WAR-DINISH-PRO.git'
    }
    stage('CB-s2-master') 
    {
        sh 'mvn package'
    }
}
