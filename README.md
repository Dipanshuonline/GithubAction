# GithubAction

Points I leant from this hands-on:
1.	Make sure all the executable elements are excess able (simply use chmod -R 777 <dir_name>) and also directories are writeable where you have to add or create a file.
E.g. Chromedrivers, java scripts, Jmeter scripts, 
2.	Always run chrome in headless mode.
[	ChromeOptions options = new ChromeOptions();
	options.setHeadless(true);
	driver = new ChromeDriver(options);			]
3.	Use Linux commands to check permission, Directory location and other details.
[	username=$(whoami)
              echo "The current user is: $username"
        	username=$(pwd)
          	echo "The current user is: $username"
          	username=$(ls -lrt)
          	echo "The current user is: $username"
          	cd Jmeter
          	username=$(ls -lrt)
          	echo "The current user is: $username"			]
4.	When using plugins other than default that come with Jmeter remember to visit ” HERE ”, this will provide with the plugin name.
5.	Always remember you have support from GITHUB, Google, and chatgpt, if you get stuck somewhere simply search it. 


Feel free to search 
1. .github/workflows/main.yml for yml file and all the stupidity I have done.
2. src/test/java/CicdSelenium/Selenium.java for simple selenium script.
3. Jmeter/AutopacingJmeter.jmx for a surprise where I have created a Autopacing script using JSR223.
