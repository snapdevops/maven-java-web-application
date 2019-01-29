node {
	stage (‘checkout’ {
		checkout scm
	   }
	stage (‘DevlopmentBuild’) {
	   steps {
                echo 'Building..'
                sh "mvn clean install"
            }
       }
	}
