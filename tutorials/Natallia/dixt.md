---
layout: tutorial
title: HANA 101 - Getting Started, and connecting the Web Workbench
description: Access your first data in a native HANA Application.
tags: [tutorial:product/sapHana, tutorial:product/hana_studio, tutorial:technology/sql, tutorial:technology/amazon_aws, tutorial:product/hcp, tutorial:interest/gettingstarted, tutorial:product/hcp_web_workbench]
---
## Prerequisites  
[How to create an SAP HANA Developer Edition in the Cloud](http://go-qa.sap.com/developer/tutorials/setup-hana-for-cloud.html)

## Next Steps
Next steps is option, hence, may not be present.
[Hello World!](http://go-qa.sap.com/developer/tutorials/hana-web-development-workbench.html)

## Details

### You will learn  

1. How to use HANA Studio Perspectives
2. How to create a connection to the HANA back end
3. Getting started with the HANA Web based development workbench

### Time to Compete

Beginners will take 30 minutes to finish this tutorial.

## Host Configuration

Access your HANA instance that was created in ["How to create an SAP HANA Developer Edition in the Cloud"](http://go-qa.sap.com/developer/tutorials/setup-hana-for-cloud.html).

Chose Notepad as the Open with Editor.

![](https://raw.githubusercontent.com/testorgiz/test-tutorials/master/tutorials/hana-configure-gt/hana_01_host_02.png)

Replace the current IP address in front of the hostname hanapm with the specific IP address for this workshop which was supplied by your instructor.

![](https://raw.githubusercontent.com/testorgiz/test-tutorials/master/tutorials/hana-configure-gt/hana_01_host_03.png)

Save the content. Exit Notepad.

![](https://raw.githubusercontent.com/testorgiz/test-tutorials/master/tutorials/hana-configure-gt/hana_01_host_04.png)


### Getting Help

If you need addition help resources beyond this document, we would suggest the following content:

* The Online Help at <http://help.sap.com/hana/SAP_HANA_Developer_Guide_en.pdf>
* The integrated help within SAP HANA Studio (content  identical to the above mentioned online help)
* SAPUI5 SDK (installed on your HANA Server) /sap/ui5/1/sdk/index.html#content/Overview.html

### Source code solutions

All source code solutions and templates for all exercises in this document can be found in the following webpage: <http://www.cnn.com/>

>### Warning
>Both the Amazon AWS and Microsoft Azure accounts will charge you for time on those cloud systems.

>If you want to create a free developer account - with no cloud VM charges - on the HANA Cloud Platform, do not follow this tutorial.  Click here to sign up for the account, and then proceed to the next tutorial.

>Note must be displayed as a "blockquote" with red backgrounnd, example, [](http://go.sap.com/developer/tutorials/setup-hana-for-cloud.html).


## HANA Studio Configuration

### ![](http://go.sap.com/dam/application/shared/icons/icon_gold_circle_01.svg) Adding the HANA Studio Perspectives

Open the HANA Studio via the Windows Start menu or via the Icon on your Start bar.

If your HANA Studio opens to the following Overview screen, simply press Workbench to return to the full Studio tooling.
![](https://raw.githubusercontent.com/testorgiz/test-tutorials/master/tutorials/hana-configure-gt/hana_01_studio_01.png)

To support the new developer centric workflow, there are two additional Eclipse Perspectives which have been added to SAP HANA Studio. These are not displayed by default.

In the upper right corner of your SAP HANA Studio, there is an add Perspectives button.  Press this.
![](https://raw.githubusercontent.com/testorgiz/test-tutorials/master/tutorials/hana-configure-gt/hana_01_studio_02.png)

>### Note

>This is a note.

>Note must be displayed as a "blockquote" with blue backgrounnd, example, [](http://hcp.sap.com/developers/TutorialCatalog/jav100_01_java_setup_eclipse.html).

Add the SAP HANA Development perspective. This is the perspective you should be using for almost this entire workshop.
![](https://raw.githubusercontent.com/testorgiz/test-tutorials/master/tutorials/hana-configure-gt/hana_01_studio_03.png)

### ![](http://go.sap.com/dam/application/shared/icons/icon_gold_circle_02.svg) Create a connection to the HANA server
Make sure you are in the SAP HANA Development perspective by clicking on the button.
![](https://raw.githubusercontent.com/testorgiz/test-tutorials/master/tutorials/hana-configure-gt/hana_01_studio_06.png)

>### Information

>This is "Information" blockqoute.

>Note must be displayed as a "blockquote" with yellow backgrounnd, example, [](http://hcp.sap.com/developers/TutorialCatalog/jav100_3_maven_based_projects.html).

Click on the “Systems” view.  Right click in the white space below this tab and choose “Add System…”.
![](https://raw.githubusercontent.com/testorgiz/test-tutorials/master/tutorials/hana-configure-gt/hana_01_studio_07.png)

Input the server hostname: hanapm

Input the instance number: 00

Enter a meaningful description of your choice.  Press the Next button.
![](https://raw.githubusercontent.com/testorgiz/test-tutorials/master/tutorials/hana-configure-gt/hana_01_studio_08.png)

## Optional - Use SSH to log in to the Linux OS
Connecting to the underlying Linux OS in the cloud instances is different for each provider.  Follow the instructions for the cloud provider you have chosen to host HANA.

### Amazon AWS
To connect to Amazon AWS, you must use the key-pair that was provided by Amazon when the instance was created.

#### Connecting to AWS from Windows

1. Using the key-pair file (\*.pem) downloaded from Amazon, create a private key file for putty using puttygen.exe.  
2. Open PuTTY on your computer, and enter the IP Address for your instance in the Host Name (or IP address) field. Click the ```Open``` button.
3. When the connection is opened, enter ‘root’ as the user. You can now change the default password for the hdbadm OS user with the command ```passwd hdbadm```. Your new password must be entered twice, and it will be checked to ensure it is sufficiently secure. Once you have entered an appropriate password twice, then you are finished!

For more detailed instructions, check out the [Amazon AWS guide to Connect Your Amazon EC2 Instance](http://docs.aws.amazon.com/gettingstarted/latest/computebasics-linux/getting-started-deploy-app-connect.html).

#### Connecting to AWS from Mac or Unix

From Linux or Mac OS-X, in terminal window, run this command: ```ssh -i [hanakey].pem [IP Address] -l root```  (Replace [hanakey].pem with the name of your key-pair file, and [IP Address] with the IP address of your instance.)

For more detailed instructions, check out the [Amazon AWS guide to Connect Your Amazon EC2 Instance](http://docs.aws.amazon.com/gettingstarted/latest/computebasics-linux/getting-started-deploy-app-connect.html).

## A few notes
* Some corporate firewalls may not allow SSH to Amazon cloud.  You may have to work with your IT organization to resolve this.
* User hdbadm owns sap software in the Linux instance. To restart the database without restarting the entire Linux instance, switch to user hdbadm and perform stop and start operations using the following commands:
    * ```su – hdbadm``` To switch user.
    * ```./HDB stop``` Command to stop HANA DB
    * ```./HDB start``` Command to start HANA DB
* The default password of user hdbadm is HANAabcd1234. You should change this password using the Linux command ```passwd hdbadm``` after creating your instance. Enter your new password (described above) when HANA Studio prompts you for the ```<SID>adm``` logon to perform administrative tasks.

## Next Steps
![](http://go.sap.com/dam/application/imagelibrary/pictograms/274000/274942.png)
Next steps is option, hence, may not be present.
[Hello World!](http://go-qa.sap.com/developer/tutorials/hana-web-development-workbench.html)
