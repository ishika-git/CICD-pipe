pipeline {
	agent any 
	
	stages {
	    stage('Checkout') {
	        steps {
			checkout scm			       
		      }}
		stage('Build') {
	           steps {
			  sh '/home/ishika/Documents/devops_software/apache-maven-3.9.6'
	                 }}
		stage('Deployment'){
		   steps {
		sh 'cp target/CICD-pipe.war /home/ishika/Documents/devops_software/apache-tomcat-9.0.85/webapps'
			}}	
}}

