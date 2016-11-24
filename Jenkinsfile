stage name:'Build'
node() {
	echo 'Build'
}

stage name:'Check'
node() {
	echo 'Check'
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
	input message: 'Do you want to deploy?', submitter: 'ops'
}
