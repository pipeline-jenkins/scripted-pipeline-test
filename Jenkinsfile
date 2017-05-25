node {
    stage('checkout') {  		
		echo 'Checking out' 			
    }
	
	stage('Build') {
        echo 'Building'
    }
	
	stage('test') {
        echo 'Running tests'
		
        def browsers = ['chrome', 'firefox']
                   
		for (int i = 0; i < browsers.size(); ++i) {
            echo "Testing the ${browsers[i]} browser"
        )
                
    }
	
	stage('package') {
        echo 'Packaging artifacts'
    }
	
	stage('deploy') {
        echo 'Deploy'
    }
}