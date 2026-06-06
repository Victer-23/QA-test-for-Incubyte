# QA-test-for-Incubyte
Gmail Compose Function Testing Assignment for Incubyte – Traditional and BDD Test Cases (Positive & Negative Scenarios)

Overview
This repository contains test cases created for the Gmail Compose functionality as part of the Incubyte QA Assessment.
The feature under test is the Gmail Compose function used to send an email with:
Subject: Incubyte
Body: QA test for Incubyte

Deliverables
The Excel workbook contains the following sheets:
1. Test Scenarios
Positive and negative test scenarios covering the Gmail Compose functionality.

2. Traditional Test Cases
Detailed test cases written using the traditional test case format, including:
Test Case ID
Test Scenario
Preconditions
Test Steps
Test Data
Expected Result

3. BDD Scenarios & Test Cases
Behavior-Driven Development (BDD) scenarios along with detailed test cases.

4. BDD Gherkin Scenarios
BDD scenarios written using Gherkin syntax:
Given
When
Then

Test Coverage
The test suite includes:
Positive Test Cases
1)Successful email composition
2)Successful email sending
3)Valid recipient validation
4)Subject and body validation

Negative Test Cases
1)Missing recipient
2)Invalid email address
3)Empty subject/body validations
4)Unsupported or invalid input scenarios

The test cases have been categorized based on:
1) Business impact
2) User experience impact
3) Functional criticality
4) Risk associated with email composition and sending

Severity Levels
Severity	           |                Description
---------------------|-------------------------------------------------------------------------------------------------------------
Critical	           |         Functionality completely blocked, email cannot be composed or sent.
High	               |          Major functionality affected, causing incorrect behavior or preventing successful email delivery.
Medium	             |          Partial functionality issue with available workaround.
Low	                 |          Minor UI, usability, formatting, or cosmetic issues.

Priority Levels
Priority	            |               Description
----------------------|---------------------------------------------------------------------------------------------------------
High (P1)	            |         Must be fixed immediately as it impacts core business functionality.
Medium (P2)	          |        Should be fixed in upcoming releases or sprints.
Low (P3)	            |         Can be addressed later as it has minimal business impact.


Author
QA Engineer
