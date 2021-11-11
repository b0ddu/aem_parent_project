Adobe Cloud Manager comes provisioned with a single git repository that is used to deploy code using Cloud Manager’s CI/CD pipelines. If your code is split across multiple repositories which is often the case in larger Adobe Experience Manager Implementations, you will need to consolidate multiple git repositories into a single git repository.

Sample Test Code showing two projects in one folder structure. 

mvn clean install -PautoInstallSinglePackage

[INFO] ------------------------------------------------------------------------
[INFO] Reactor Summary:
[INFO]
[INFO] WKND Sites Project - Reactor Project 1.0.1-SNAPSHOT  SUCCESS [  0.298 s]
[INFO] WKND Sites Project - Core 1.0.1-SNAPSHOT ........... SUCCESS [ 10.340 s]
[INFO] WKND Sites Project - UI Frontend 1.0.1-SNAPSHOT .... SUCCESS [ 13.274 s]
[INFO] WKND Sites Project - UI apps structure 1.0.1-SNAPSHOT SUCCESS [  1.352 s]
[INFO] WKND Sites Project - UI apps 1.0.1-SNAPSHOT ........ SUCCESS [  6.190 s]
[INFO] WKND Sites Project - UI content 1.0.1-SNAPSHOT ..... SUCCESS [  3.735 s]
[INFO] WKND Sites Project - UI config 1.0.1-SNAPSHOT ...... SUCCESS [  0.251 s]
[INFO] WKND Sites Project - UI sample content 1.0.1-SNAPSHOT SUCCESS [  8.266 s]
[INFO] WKND Sites Project - All 1.0.1-SNAPSHOT ............ SUCCESS [01:01 min]
[INFO] WKND Sites Project - Integration Tests 1.0.1-SNAPSHOT SUCCESS [ 12.151 s]
[INFO] WKND Sites Project - UI Tests 1.0.1-SNAPSHOT ....... SUCCESS [  0.418 s]
[INFO] aem_parent_project 1.0.0-SNAPSHOT .................. SUCCESS [  0.098 s]
[INFO] WKND Sites Project - Dispatcher 1.0.0-SNAPSHOT ..... SUCCESS [  0.628 s]
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time:  02:00 min
[INFO] Finished at: 2021-11-11T00:46:57-05:00
[INFO] ------------------------------------------------------------------------