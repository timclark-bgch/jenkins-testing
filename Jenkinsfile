#!/usr/bin/env groovy

stage name:'Build'
node() {
	echo 'Build'
	withEnv(['VENV=$WORKSPACE/.venv']) {
		sh 'echo $VENV'
	}
	echo 'DONE'
	sh 'python --version'
	sh 'which python'
	sh 'java -version'
	sh 'which virtualenv'
}

stage name:'Check'
node() {
	echo 'Check'
	echo 'Boom!'
	echo 'Bang!'
}

stage name:'Deploy to DEV'
node()	{
	echo 'Deploy to DEV'
}

stage name:'Deploy to QA'
node()	{
	echo 'Deploy to QA'
}

stage name:'Deploy to PROD'
node()	{
	echo 'Deploy to PROD'
}
