node('master') 
{
    stage('CD-s1') 
    {
    git 'https://github.com/BABJI-AWS-DEVOPS/MAVN-WAR-DINISH-PRO.git'
    }
    stage('CB-s2') 
    {
        sh 'mvn package'
    }
}
