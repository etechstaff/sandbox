pipeline {
	agent any 
	stages{
		stage('1-clonecode'){
			steps{
			    checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'jenkins-acess', url: 'https://github.com/etechstaff/sandbox.git']])
			}
		}
		stage('armand'){
			steps{
				echo "member 1: armand"
			}
		}
		stage('kenu'){
			steps{
				echo "member 2: kenu"
			}
		}
		stage('bruno'){
			steps{
				echo "member 3: bruno"
			}
		}
        stage('eric'){
            steps{
                echo "member 4: eric"
            }
        }
        stage('bazil'){
            steps{
                echo "member 5: bazil"
            }
        }
	}
}
