
pipeline{
	agent any
	stages{
		stage('1-cloning'){
			steps{
				checkout scmGit(branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'git', url: 'https://github.com/Etech-team5-group6/team5-Analytic.git']])
			}
		}
		stage('2-saada1-contribution'){
			steps{
				sh 'lscpu'
				sh 'sudo systemctl status jenkins'
			}
		}

		stage('3-Nellyblues-contribution'){
			steps{
				sh 'lscpu'
				sh 'sudo systemctl status jenkins'
			}
		}

		stage('4-Fancis-contribution'){
			steps{
				sh 'df -h'
				sh 'sudo systemctl status jenkins'



			}
		}	


	}
}
