# Title Page
**University of Technology Sydney**

**Faculty of Engineering and Information Technology**

**31257: Information System Development Methodologies**

**Design Thinking and Scrum Activities Assessment**

**Due Date:**

2nd June 2020

**Name of Students: **

13229594 Mark Gonzales

13568718 Aryan Gupta

13243682 Brendan Kaihe

13202472Christian John

## Table of Contents
Title Page 1

Executive Summary  3

Body of The Report 3

1. Objectives  3
2. Stakeholders 3
3. Design Thinking 4

3.1 Empathy 4

3.2 Define 5

3.3. Ideate 6

4. Use Cases 7

4.1 Assumptions 7

4.2 User Stories 8

4.3 Use Case Diagrams 9

4.4 Use Case Narratives 10

5. Objects and Classes 14

5.1 Class Diagram 14

6. Run Time Model 15

6.1 Sequence Diagrams 15

6.2 Activity Diagrams 17

7. Iterative Approach 19

7.1 Team Roles 19

7.2 Product Backlog 19

7.3 Sprints 20

7.3.1 Sprint 1 20

7.3.2 Sprint 2 20

7.3.3 Sprint 3 20

7.3.4 Sprint 4 21

8. Evaluation of Scrum 21

9. System Evaluation 22

9.1 Benefits  22

9.2 Possible Failures 23

10. References 24

## Executive Summary
A major travel company is pushing innovative efforts to improve their in-house Call Management Centre (CMC) and is seeking professional assistance in developing a new information system. This report aims to identify, analyse and evaluate the existing CMC, in order to improve the current system and align key stakeholder requirements. The report will identify key stakeholders and address their issues in relation to call flow control, provision of service to end customers, integration of a profiler tool and matching users based on profiles. Through the use stages 1 and 2 of the design thinking process, the report will design and formulate ideas based on the existing system. Additionally, key assumptions are identified and various models are produced to provide an in depth analysis on the scope, functions and processes of both the current and proposed system.
## Body of the report
### 1. Objectives
The overall objective of the major travel company is to develop a new information system which improves the current operation of their in-house call management centre. Specifically, the following goals for the system have been identified:

- Improve call routing and dynamic call flow control for inbound and outbound calls
- Provide more assistance to relationship managers in their ability to provide an improved service to end customers
- Integrate a profiler tool to set and track profiles of users within the system
- Match relationship managers and end customers according to their profiles
### 2. Stakeholders
| Stakeholder | Responsibility | Concerns | Operations |
| --- | --- | --- | --- |
| Customer | Call and book holiday packages with the travel company |
- Assistance in booking a holiday package
- Security of personal information stored
 |
- Contact Company
- Order Packages

- Complete payments
 |
| Relationship Manager | Provide customers with adequate service to secure packages |
- Provision of accurate data from system
 |
- Connect to customers

-  Handle transactions

-  Provide service
 |
| Business Manager | Identify improvements to the system |
- Inefficient existing operations
 |
- Strategize plans to improve efficiency
 |
| Travel Company Owner | Executive of overall business |
- Inefficient operation  of in-house call management centre
 |
- Oversee company
 |
 Please refer to PDF report file
 
### 3. Design Thinking
#### 3.1 Empathy
(RackMultipart20200602-4-nxtgeo_html_edf4a505242fd6b3.png) Please refer to PDF report file
#### 3.2 Define
A major travel company is pushing innovative efforts to improve their in-house Call Management Centre (CMC) and is seeking professional assistance in developing a new information system. Within the company are Relationship Managers, who&#39;s role is to satisfy current and potential customers with travel needs. Business managers of the company strategize that an upgrade of their in-phone sales activities (inbound/outbound call rating and call flow rate) is a huge asset to RM&#39;s sales motives and offer customers the best in-phone service experience with the company. Considering the vast amount of travel packages offered by the company, the new information system will improve call flow rate by allowing a more effective alignment of customers with specific needs and Relationship Managers with the appropriate portfolio to deliver customer satisfaction.

As a way of matching the right customer to the right Relationship Manager, the system embodies a &#39;Profiler Tool&#39; in which sets a profile for both users of the systems. Attributes within these profiles feed the decision-making system in allocation of Relationship Manager and Customers. From this, business managers hope to expect a better customer experience which leads to growth in customer relationship and profitable gains.

To add upon the profiler feature of the system, it is worth mentioning that Relationship Managers are also evaluated and scaled based on the effectiveness and efficiency of their sales performance. Conversely, customers are also scored from 1-10 based upon their transaction history and call frequency with the travel company.

When Relationship Managers make outbound calls as a means to promote products and attract potential buyers. The system offers relationship managers a &#39;target list&#39; of customers that suspects commonalities of attributes between RM and the customer. When making these outbound calls, the system prepares Relationship Managers with reference to customer profile and an outlined script of their sales activity.

For customers wishing to inquire and purchase travel packages through inbound calls, their dials are redirected to the Call Management Centre that prioritise their calls. As a means to maximise call handling effectiveness, customers with the highest score are prioritised and directed to their appropriate RM manager. Furthermore, inbound traffic calls can occur leading uncertain wait time for customers. To compensate this, the system manages these in-dial waiting customers to an Interactive Voice Response unit to gather information of their needs which then redirects them to an Automatic Call Distributor to segment callers to their appropriate Relationship Manager when ready.

Point of View Statements

As a customer, the current system:

- Can take too long to connect to someone to talk about holiday packages especially when its busy, making it a tedious process
- Calling the company is time consuming and is dependent on the reliability of staff and phone lines
- May not be providing me with the package which best suits my wants

As a Relationship Manager, the current system:

- Doesn&#39;t provide me with enough information to best suit each unique individual and tailor their preferences
- Lacks the ability to match me with potential customers where my skills are of use when it comes to securing deals

As the owner, the current system:

- Lacks efficiency when it comes to connecting customers and relationship managers

#### 3.3 Ideate
How Might We Statements

- How might we retain and upgrade customer loyalty
- How might we better handle fraudulence of customer information and transaction
- How might we protect the data of consumers
- How might we find a way to upsell consumers
- How might we innovate the profiler tool of the system
- How might we upskill selling interactions of RM
### 4. USE Cases

- Refer to github repository or report.pdf

#### 4.1 Assumptions

- Refer to github repository or report.pdf

#### 4.2 User Stories

- Refer to github repository or report.pdf

#### 4.3 Use Case Diagrams

- Refer to github repository or report.pdf

#### 4.4 User Case Narratives

| **USE Case ID** | UC101: Inbound Calls |
| --- | --- |
| **User Story** | US004: As a customer I want to connect to a suitable relationship manager who matches my criteria, so that my preferences are understood properly |
| **Goal** | Customer gets the best deal on their holiday package. |
| **Priority** | High |
| **Actors** | Primary Actor - CustomerSecondary Actor - Relationship Manager, Automatic Call Distributor, Profiler Tool, Interactive Response unit |
| **Pre-Conditions** | The customer has access to the travel company&#39;s phone line |
| **Post Conditions** | The customer has connected with a relationship manager and/or booked a holiday package |
| **Trigger** | The Customer calls the travel company |
| **Main Flow** |
1. Customer dials the travel company&#39;s phone number
2. Automatic call distributor receives the customer&#39;s call. If the customer calls during peak hours refer to **Alternate Flow 1 : Peak Hour Inbound Calls**
3. Customer connects with automatic call distributor
4. Automatic call distributor requests customer&#39;s information
5. Customer provides information
6. Profiler tool creates unique caller ID and collects customer&#39;s information and creates a new customer profile. If the customer is an existing customer refer to **Alternate Flow 2: Existing Customer**
7. Profiler tool scores customers profile
8. Automatic call distributor sets the priority of the call
9. Profiler tool matches call with an RM profile, creating sales script about the customer
10. Relationship manager reviews customer information and sales script
11. Automatic call distributor routes customers call to an appropriate relationship manager
12. Relationship manager answers customers call
13. Use Case Ends
 |
| **Exceptions** | **Exception 1.** Step 4: System is unavailable when the profiler tool attempts to create a new customer profile. **Exception 2.** Steps 1-11: Customer ends the call at any time, prompting the profiler tool to end its current session. |
| **Includes/Extends/Inherits** | N/A |
| **Supporting Information** | Customer information needs to be stored on a central server |
| **Non - functional requirements** | Performance/Connectivity: All calls should be flowing and not interrupted by any connectivity issues |

| **Alternate Flow 1** | &quot;Peak hour inbound calls&quot; |
| --- | --- |
| **Trigger** | The customer calls the travel company during peak hour |
| **Step** | 1. Interactive response unit sends customer prompt options 2. Customer responds to prompt options3. Interactive response unit processes customer&#39;s response4. Rejoin step 4 in the main flow.
 |
| **Post conditions** | The automatic call distributor is able to process the customers information and send it to the profiler tool |
| **Exceptions** | **Exception1.** Steps1-3: Customer ends the call any time, causing the interactive response unit to end the session. |

| **Alternate Flow 2** | &quot;Existing customer&quot; |
| --- | --- |
| **Trigger** | The customer calling the travel company is an existing customer |
| **Step** | 1. Profiler tool retrieves customer&#39;s profile2. Rejoin step 7 in the main flow. |
| **Post conditions** | Profiler tool retrieves customer&#39;s profile |
| **Exceptions** | **Exception1.** Step1: Customer ends the call at any time, causing the profiler tool to end the session. |

| **USE Case ID** | UC102: Outbound Calls |
| --- | --- |
| **User Story** | As a Relationship Manager, I want to receive the correct information and guidelines from the system so that I can provide an improved service to the end-customer. |
| **Goal** | Provide the targeted customer with improved service and attract potential buyers |
| **Priority** | High |
| **Actors** | Primary Actor: Relationship ManagerSecondary Actor: Customer, Call Management System, Profiler Tool |
| **Pre-Conditions** | The Relationship Manager has access to the Call Management System.Database with customer details exists within the system. |
| **Post Conditions** | The Relationship Manager has successfully been connected to a customer |
| **Trigger** | The Relationship Manager is assigned a number by the system and calls the customer. |
| **Main Flow** |
1. The Call Management System retrieves customer details from the database.
2. The system generates a unique target list for each Relationship Manager based on their skills and profile identified by the profiler tool.
3. The system displays the customer details and provides the Relationship Manager with guidelines and a script.
4. Relationship Manager reviews information and receives a unique call ID.
5. Relationship Manager connects to customer. Refer to Alternate flow 1: **Call not connected**
6. provides unique call ID to customer
7. Profiler tool scores and updates existing profiles of both Relationship Manager and customer based on outcome of call.
8. Steps 3-7 are repeated till the end of the target list is reached.
9. Use Case ends.
 |
| **Exceptions** | **2**
 |
| **Includes/Extends/Inherits** | NA |
| **Supporting Information** | Relationship Managers are already initialised within the system |
| **Non - functional requirements** | Security: All customer details must be kept securePerformance: Calls to a customer must be connected in under 30 seconds |

| **Alternate Flow 1** | &quot;Call not connected&quot; |
| --- | --- |
| **Trigger** | Relationship Manager is unable to reach potential customer |
| **Step** |
1. Profiler tool adjusts customer profile
2. Rejoin at step 4 in the main flow.

 |
| **Post conditions** | Relationship Manager proceeds to the next targeted customer |
| **Exceptions** | End of the target list is already reached, then the use case ends. |

### 5 Objects and Classes
#### 5.1 Class Diagram

- Refer to github repository or report.pdf

### 6. Run time Model
- Refer to github repository or report.pdf
#### 6.1 Sequence Diagrams
- Refer to github repository or report.pdf
#### 6.2 Activity Diagrams
- Refer to github repository or report.pdf

### 7. Iterative Approach
#### 7.1 Team Roles
#### 7.2 Product Backlog
#### 7.3 Sprints
##### 7.3.1 Sprint 1
##### 7.3.2 Sprint 2
##### 7.3.3 Sprint 3
##### 7.3.4 Sprint 4
### 8. Evaluation
### 9. System Evaluation
#### 9.1 Benefits
#### 9.2 Possible Failures
## References

## Appendicies
### Appendix 1A

