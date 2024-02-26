pipeline{ 
	agent any 
		stages{ 
			stage("git"){ 
				steps{ 
					git "https://github.com/PraveenRaj106/Feb_26.git" 
				} 
			} 
			stage("run"){ 
				steps{ 
					sh "python main.py" 
					sh "java Demo.java" 
				} 
			} 
		} 
}
