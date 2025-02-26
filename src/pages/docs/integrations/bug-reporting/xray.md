---
title: "Xray Integration with Testsigma"
page_title: "Xray Integration with Testsigma"
metadesc: "Xray is a Test Management tool that gives the structure to organize, plan, and report the progress of testing. Learn how to integrate Xray with Testsigma"
noindex: false
order: 16.37
page_id: "Xray Integration with Testsigma"
warning: false
contextual_links:
- type: section
  name: "Contents"
- type: link
  name: "Prerequisites"
  url: "#prerequisites"
- type: link
  name: "Steps to Integrate Xray with Testsigma"
  url: "#steps-to-integrate-xray-with-testsigma"
- type: link
  name: "Steps to Link an Xray Test Case to a Testsigma Test Case"
  url: "#steps-to-link-an-xray-test-case-to-a-testsigma-test-case"
- type: link
  name: "Steps to link an Xray test set to a Testsigma test suite"
  url: "#steps-to-link-an-xray-test-set-to-a-testsigma-test-suite"
- type: link
  name: "Steps to link an Xray test plan to a Testsigma test plan"
  url: "#steps-to-link-an-xray-test-plan-to-a-testsigma-test-plan"
---

---

Xray is a test management tool that provides the structure to organize, plan, and report with accuracy on the progress of testing as well as the readiness to deploy. This article discusses Xray integration with Testsigma.

With Xray integration, you can link:
- An Xray test case to a Testsigma test case.
- An Xray test set to a Testsigma test suite.
- An Xray test plan to a Testsigma test plan.

---
 
## **Prerequisites**
- A working JIRA integration. For more information, refer to [jira bug reporting](https://testsigma.com/docs/integrations/bug-reporting/jira/).
- A working Xray integration. 
    - JIRA Account URL
    - Client ID
    - Client Secret 

*For more information, refer to [global settings](https://docs.getxray.app/display/XRAYCLOUD/Global+Settings%3A+API+Keys).*

---
 
## **Steps to Integrate Xray with Testsigma** 
1. Navigate to **Settings > Integrations**.
![Integrations](https://s3.amazonaws.com/static-docs.testsigma.com/new_images/projects/applications/ytintegrations.png)

2. Enable toggle on **Xray** widget.
![Xray Toggle](https://s3.amazonaws.com/static-docs.testsigma.com/new_images/projects/applications/xraytoggle.png)

3. On the **Xray Details** prompt, enter **Jira Account URL**, **Client Id** and **Client Secret**.
![Xray Details](https://s3.amazonaws.com/static-docs.testsigma.com/new_images/projects/applications/xraydetails.png)

4. Click on **Save & Enable**.
![Save & Enable](https://s3.amazonaws.com/static-docs.testsigma.com/new_images/projects/applications/detailsxray.png)

[[info | **NOTE**:]]
| If you want to add attachments like logs, screenshots, and videos of execution for the test executions, please check the **Add Attachments to Test**.

Here's a quick GIF demonstrating how to integrate Xray with Testsigma. 
![Xray Integration](https://s3.amazonaws.com/static-docs.testsigma.com/new_images/projects/applications/xrayint.gif)

---

## **Steps to Link an Xray Test Case to a Testsigma Test Case**
1. Get the ID of an already created test from Xray. For example, if my test url on Xray is https://testserver.atlassian.net/browse/test75, then the ID would be: ***test75***

2. Navigate to the test case details page corresponding to the test case you want to link with.
![Test Case Details](https://s3.amazonaws.com/static-docs.testsigma.com/new_images/projects/applications/xraytcsbox.png)

3. Enter **Xray ID** and click on click on the link button. 
![Xray Link](https://s3.amazonaws.com/static-docs.testsigma.com/new_images/projects/applications/xrayidlink.png)

---

## **Steps to Link an Xray Test Set to a Testsigma Test Suite**
1. Get the ID of an already created test set from Xray. For example, if my test set url on Xray is https://testserver.atlassian.net/browse/ts85, then the ID would be: ***ts85***

2. Navigate to the test suite details page corresponding to the test suite you want to link with.
![Test Suites](https://s3.amazonaws.com/static-docs.testsigma.com/new_images/projects/applications/testsuitenav.png)

3. Enter **Xray ID** and click on click on the link button. 
![Link](https://s3.amazonaws.com/static-docs.testsigma.com/new_images/projects/applications/tslink.png)

[[info | **NOTE**:]]
| For the test execution of all the test cases inside the test suite, the test cases should also be linked to appropriate test cases on Xray.

---

## **Steps to Link an Xray Test Plan to a Testsigma Test Plan**
1. Get the ID of an already created test plan from Xray. For example, if my test plan URL on Xray is: https://testserver.atlassian.net/browse/tp95, then the ID would be: ***tp95***

2. Navigate to the test plan details page corresponding to the test plan you want to link with.
![Test Plans](https://s3.amazonaws.com/static-docs.testsigma.com/new_images/projects/applications/tpnav.png)

3. Enter **Xray ID** and click on click on the link button.
![Test Plan Xray ID](https://s3.amazonaws.com/static-docs.testsigma.com/new_images/projects/applications/tplink.png)

[[info | **NOTE**:]]
| When you execute a Test Plan in Testsigma, the execution status will be updated for the linked test sets in Xray. 

---

Here's a quick GIF demonstrating how to link Xray IDs with Test Cases, Test Suites & Test Plans with Testsigma.
![Xray Links](https://s3.amazonaws.com/static-docs.testsigma.com/new_images/projects/applications/tcstsstpsxray.gif)

---