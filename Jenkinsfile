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
		stage('KING NR'){
			steps{
				echo "KINGSLY NR"
			}
		}
        stage('eric'){
            steps{
                echo "member 4: eric"
            }
        }
        stage('adding README FILE'){
            steps{
                sh "bash -x cp  README.md demofolder"
            }
        }
	}
}
