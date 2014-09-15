Steps to run robot framework test cases in Mac machine:

1. The machine should have python 2.7 if not please install it.

2. Install the below libraries:
	pip install --quiet robotframework
	pip install --quiet robotframework-httplibrary
	pip install --quiet robotframework-selenium2library
	pip install --quiet robotframework-randomlibrary

3. Navigate upto the location where the file 'test_repeated_invoice.txt' is located.

4. Run the test using the below command:
   pybot -L TRACE test_repeated_invoice.txt

5. To view the report, please open 'report.html' file generated at same location. I have attached a sample report which I was generated for this test case.




In case you want to run the tests in Linux machine, please check the link "http://dailychitty.blogspot.in/2014/07/configuring-jenkins-agent-to-run-robot.html" to install the robot-framework related libraries.
