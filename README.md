Adobe Cloud Manager comes provisioned with a single git repository that is used to deploy code using Cloud Manager’s CI/CD pipelines. If your code is split across multiple repositories which is often the case in larger Adobe Experience Manager Implementations, you will need to consolidate multiple git repositories into a single git repository.

Sample Test Code showing two projects in one folder structure. 

mvn clean install -PautoInstallSinglePackage<br>

[INFO] ------------------------------------------------------------------------<br>
[INFO] Reactor Summary:<br>
[INFO]<br>
[INFO] WKND Sites Project - Core 1.0.1-SNAPSHOT ........... SUCCESS [ 12.007 s]<br>
[INFO] WKND Sites Project - UI Frontend 1.0.1-SNAPSHOT .... SUCCESS [ 14.875 s]<br>
[INFO] WKND Sites Project - UI apps structure 1.0.1-SNAPSHOT SUCCESS [  1.148 s]<br>
[INFO] WKND Sites Project - UI apps 1.0.1-SNAPSHOT ........ SUCCESS [  7.453 s]<br>
[INFO] WKND Sites Project - UI content 1.0.1-SNAPSHOT ..... SUCCESS [  3.898 s]<br>
[INFO] WKND Sites Project - UI config 1.0.1-SNAPSHOT ...... SUCCESS [  0.410 s]<br>
[INFO] WKND Sites Project - UI sample content 1.0.1-SNAPSHOT SUCCESS [  9.638 s]<br>
[INFO] WKND Sites Project - All 1.0.1-SNAPSHOT ............ SUCCESS [01:03 min]<br>
[INFO] WKND Sites Project - Integration Tests 1.0.1-SNAPSHOT SUCCESS [ 33.143 s]<br>
[INFO] WKND Sites Project - UI Tests 1.0.1-SNAPSHOT ....... SUCCESS [  0.352 s]<br>
[INFO] Platform Services 1.0.1-SNAPSHOT ................... SUCCESS [  0.010 s]<br>
[INFO] aem_parent_project 1.0.0-SNAPSHOT .................. SUCCESS [  0.084 s]<br>
[INFO] WKND Sites Project - Dispatcher 1.0.0-SNAPSHOT ..... SUCCESS [  0.521 s]<br>
[INFO] wknd-spa-react 1.0.3-SNAPSHOT ...................... SUCCESS [  4.508 s]<br>
[INFO] WKND SPA React - Core 1.0.3-SNAPSHOT ............... SUCCESS [ 42.785 s]<br>
[INFO] wknd-spa-react.ui.frontend - UI Frontend 1.0.3-SNAPSHOT SUCCESS [01:46 min]<br>
[INFO] WKND SPA React - Repository Structure Package 1.0.3-SNAPSHOT SUCCESS [  0.826 s]<br>
[INFO] WKND SPA React - UI apps 1.0.3-SNAPSHOT ............ SUCCESS [ 10.033 s]<br>
[INFO] WKND SPA React - UI content 1.0.3-SNAPSHOT ......... SUCCESS [  1.507 s]<br>
[INFO] WKND SPA React - All 1.0.3-SNAPSHOT ................ SUCCESS [  2.258 s]<br>
[INFO] WKND SPA React - Integration Tests 1.0.3-SNAPSHOT .. SUCCESS [ 11.803 s]<br>
[INFO] ------------------------------------------------------------------------<br>
[INFO] BUILD SUCCESS<br>
[INFO] ------------------------------------------------------------------------<br>
[INFO] Total time:  05:33 min<br>
[INFO] Finished at: 2021-11-12T00:46:18-05:00<br>
[INFO] ------------------------------------------------------------------------<br>