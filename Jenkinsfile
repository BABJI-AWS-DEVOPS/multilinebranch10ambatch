node('master') 
{
    stage('CD-s1-payment') 
    {
    git 'https://github.com/BABJI-AWS-DEVOPS/MAVN-WAR-DINISH-PRO.git'
    }
    stage('CB-s2-payent') 
    {
        sh 'mvn package'
    }
}
