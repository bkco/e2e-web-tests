# End to End Testing Project for Web Frontend

## Project Purpose
1.	Skeleton project that enables Product Owners to write BDD style unit tests.
2.	Technically the project demos how tests can be run as part of a continuous integration process running on gitlab. XVFB enables browsers to be run in the CI environment.
3.	Utilises a custom docker containing chrome, nightwatch and a node.js environment publishes to docker-hub.


## Run project locally
	npm install
	npm run test-chrome
	
## Project dependency overview
    npm install nightwatch --save-dev          // test framework
	npm install selenium-server-standalone-jar --save-dev
	npm install phantomjs-prebuilt --save-dev
    npm install cucumber --save-dev            // cucumber dependency
	npm install chromedriver --save-dev        // chrome driver
	npm install geckodriver --save-dev         //firefox driver
	npm install selenium-webdriver --save-dev  //safari driver



	
			
    