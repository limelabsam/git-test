node ('master'){
	stage 'Checkout'
		checkout scm
		sh 'qmake'
	stage 'Tests'
		sh 'make check'
}