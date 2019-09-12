# LocatorsErrors_JS-WDIO
https://docs.google.com/spreadsheets/d/1x2mwodQNhiS3vL5xeYL1rC5IAwLQVHuj1Gb53y89Buc/edit#gid=0



# TA locator is invalid.	"1. Open command line and run 
""git clone https://github.com/ShapovalovII/LocatorsErrors_JavaScript-WebdriverIO.git""
2. Run ""wdio wdio.conf.js --spec ./test/specs/test_scenario/InitialLocatorWithInvalidTAname.js"""	
* Expected error: TrueAutomation locator ta-Name contains unsupported characters. Please make sure to use only letters, numbers, colon and underscore symbols in locator names.	
* Actual error: TrueAutomation locator ta-Name contains unsupported characters. Please make sure to use only letters, numbers, colon and underscore symbols in locator names.
# Element was not found on the page by initial locator.
"1. Open command line and run 
""git clone https://github.com/ShapovalovII/LocatorsErrors_JavaScript-WebdriverIO.git""
2. Run ""wdio wdio.conf.js --spec ./test/specs/test_scenario/InitialLocatorNotExistOnUsePage.js"""	
* Expected error: NOT_FOUND	* 
* Actual error: NOT_FOUND
# Initial locator is invalid.	
"1. Open command line and run 
""git clone https://github.com/ShapovalovII/LocatorsErrors_JavaScript-WebdriverIO.git""
2. Run ""wdio wdio.conf.js --spec test/specs/test_scenario/TAlocatorWithInvalidInitialLocator.js"""	"
* Expected error:
1) Expected error: Unable to locate element { using: ""css selector"", selector: "".RveJvd snByac"" }
2) Expected error: Unable to locate element { using: ""css selector"", selector: ""![id='identifierNext']"" }
3) Expected error: Unable to locate element { using: ""css selector"", selector: ""span[@class='RveJvd snByac']"" }
4) Expected error: Unable to locate element { using: ""css selector"", selector: ""!*=Справка"" }"	"
* Actual error: 
1) Actual error: Unable to locate element { using: ""css selector"", selector: "".RveJvd snByac"" }
2) Actual error: Unable to locate element { using: ""css selector"", selector: ""![id='identifierNext']"" }
3) Actual error: Unable to locate element { using: ""css selector"", selector: ""span[@class='RveJvd snByac']"" }
4) Actual error: Unable to locate element { using: ""css selector"", selector: ""!*=Справка"" }"
# Element was not found on the page by TA locator.	
"1. Open command line and run 
""git clone https://github.com/ShapovalovII/LocatorsErrors_JavaScript-WebdriverIO.git""
2. Run ""wdio wdio.conf.js --spec test/specs/test_scenario/TAlocatorInDatabase.js"""	
* Expected error: NOT_FOUND	
* Actual error: NOT_FOUND
# TA locator was not found in database.	
"1. Open command line and run 
""git clone https://github.com/ShapovalovII/LocatorsErrors_JavaScript-WebdriverIO.git""
2. Run ""wdio wdio.conf.js --spec test/specs/test_scenario/TAlocatorNotInDatabase.js"""	
* Expected error: NOT_FOUND	
* Actual error: NOT_FOUND
