pipeline{

	agent any
	
	stages{
	    
	    stage("build")
	    {
	    	steps{
	    	    echo("build the priject")
	    			}
			}
			
			
			stage("Run Security scan")
	    {
	    	steps{
	    	    echo("Security testing using burp suite")
	    			}
			}
			
			stage("Run unit Test")
	    {
	    	steps{
	    	    echo("Run UTs")
	    			}
			}
			
			stage("Deploy to dev")
	    {
	    	steps{
	    	    echo("Deploy to dev")
	    			}
			}
			
			stage("Deploy to QA")
	    {
	    	steps{
	    	    echo("Deploy to QA")
	    			}
			}
			
	    
	    
	    stage("Run the Regression test case on QA")
	    {
	    	steps{
	    	    echo("Run regression test case on QA")
	    		}
		}
	}
}
