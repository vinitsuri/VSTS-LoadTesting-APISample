# VSTS-LoadTesting-APISample
VSTS Cloud-based Load Testing API Sample

##Introduction
This sample enables the user to run a load test using the "Visual Studio Team Services - Cloud-based Load Testing Service"

##Description
The sample provides the following functionalities to run a load test using the "Visual Studio Team Services - Cloud-based Load Testing Service"

| Syntax                                       | Description                                                 |
| :-------------                                |:-----------------------------------------------------------|
| /testruns                                    | fetches the test runs for the account                       |
| /gettestrunsbyname <testrunname>             | fetches the test runs filtered by name                      |
| /gettestrunsbystatus <testrunstatus>         | fetches the test runs filtered by status                    |
| /gettestrunsbydays <for last how many days>  | fetches the test runs filtered by days                      |
| /starttestrun                                | queues and starts a test run on the service                 |
| /testrun <testrunid>                         | fetches a single test run details using the test run id     |
| /downloadresult <testrunid>                  | downloads the test run results                              |
| /downloaddiagnosticdata <testrunid>          | downloads the diagnostic data associated with a test run    |
| /gettestrunmessages <testrunid>              | fetches the test run messages for a test run                |
| /getavgresponsetime <testrunid>              | fetches the avg response time for a test run                |
| /getuserload <testrunid>                     | fetches the user load for a test run                        |

Note : This sample requires you to use a "Personal Access Token" for authentication. You will need to explicitly enable PAT tokens for your account and provide it in the app.config file. Details on how to enable it can be found  @ http://roadtoalm.com/2015/07/22/using-personal-access-tokens-to-access-visual-studio-online/
 
 
