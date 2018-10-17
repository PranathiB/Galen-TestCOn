# Galen
This project uses Galen Framework for UI Automation with Galen version 2.0.7

#####Installing Galen:

Download and install galen from the following link

http://galenframework.com/download/

#####Verify the installation using the following command
```
galen -v
```
#####To run the test, use the following command

galen test NameOfTheTestFile --htmlreport ReportFolderPath

Example:
```
galen test testcon.test --htmlreport html-report
```
#####To run the spec file alone, use the following command

galen check NameofTheSpecFile --url URLOfTheWebsite --size ResolutionOfScreen --include RelevantTags --htmlreport ReportFolderPath

Example:
```
galen check testcon.gspec --url http://testcon.lt --size 1280x1024 --include desktop --htmlreport reports

```
