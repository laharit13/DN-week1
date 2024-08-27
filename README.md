# DN-week1
# Module 1 - ServiceNow Platform and Development Fundamentals

Servicenow is a cloud based platform for IT operations,HR andcustomer service.

It automates and streamlines business processes.

It is both customizable and scalable.

Key features are ITSM, CSM, HRM, Asset Management, PPM, BPM.

Service now is Widely used across industries.

*The key components for the architecture of Servicenow are:*

- Service Catalog: One place where all services you want can be found by users.
- Service desk: Its function is that of an interface between end-users and IT professionals during the process of fulfilling requests.
- CMDB (Configuration Management Database): It houses all information about IT assets as well as services.
- Workflow engine: This is an automation mechanism which aids in managing business processes.
- Reporting and analytics: These are tools required to generate reports as well as analyze data sets.

ServiceNow provides numerous applications that cater for different business requirements. This includes the most popular applications such as:

- IT Service Management (ITSM)
- Customer Service Management (CSM)
- Human Resources Management (HRM)
- Asset Management
- Project Portfolio Management (PPM)
- Business Process Management (BPM)

Business processes are automated by ServiceNow through workflows. These workflows can be developed and modified in order to outline the stages of a process along with the circumstances that prompt actions.

Elements of the Interface are:

- Header: It holds ServiceNow’s emblem, search disciplines and also navigation table.
- Navigation Menu: It enables one to use various programs and modules.
- Dashboard: Shows personalized notes along with widgets.
- Form: It is an area used for displaying and modifiying information.
- List: It is a tabular representation of logs.
- Related Lists: Displays similar logs on a form.
- Activity Stream: Displays recent actions and updates.
- ServiceNow UI is easy to navigate and user friendly interface. It comprises of a dashboard, search bar, and menu for accessing different applications and features.
- Navigation: The application navigater which allows quick access. 
- Bookmarks: Most used things are marked as favorites. 
- History: The latest activities are tracked. 
- Permissions: ACLs used to control access. 
- Customization: UI policies that determine appearance, business rules that guide automation and client scripting in cases of engaging with users and interacting with them.

**Forms in Servicenow**

Standard Layout:

The standard layout for ServiceNow forms includes the following :

- Header: Contains the form title, record number, and actions.
- Form Body: Displays the form fields and related lists.
- Footer: Contains buttons for saving, canceling, and related actions.

Form Field Types are:

- Single-line text: For short text inputs.
- Multi-line text: For longer text inputs.
- Number: For numerical values.
- Date: For dates.
- DateTime: For dates and times.
- Reference: For referencing other records.
- Choice list: For selecting options from a predefined list.
- Reference qualifier: For filtering reference fields based on conditions.
- Calculated: For calculating values based on other fields.

The forms consist of various things such as:

- Form sections
- Related lists and formatters
- Form views
- Form personalization
- Adding attachments
- Form templates etc.

**Importing Data in Servicenow**

To import means from outside systems ServiceNow has different integration methods. Some of the well-known ones are:

1. REST API Integration

Method: Makes use of ServiceNow’s REST API to create, read, update and delete (CRUD) records programmatically.

Process:
- Get required authentication credentials (client ID and client secret).
- Build API requests according to your desired actions and data.
- Send requests to the ServiceNow instance for processing.
- Parse responses in order to handle success or errors

Tools: Postman, curl , programming languages (Python, JavaScript, etc.).

2. Integration of SOAP API

Method: This approach employs the ServiceNow SOAP API for more complicated collaborations and relationships with external systems.

Process:
- Create WSDL files that specify the API interface.
- Utilize a SOAP client to connect with the ServiceNow instance.
- Achieve data management by exchanging XML messages through CRUD (Create, Read, Update and Delete).

Tools: SOAPUI, programming languages (Java, .NET).

3. Import sets

Method: Using an in-built ServiceNow feature that allows you to import data from CSV or Excel files

Steps:
- Create an import set record
- Configure the import set to map external fields to ServiceNow fields
- Upload the data file
- Run the import set to import the data

Limitations: May have limitations for large datasets or complex mappings.

4. Integration Hub

Method: An integrated centric platform that enables ServiceNow to connect or work with more than one system.

Process:
- Establish the integration.
- Set up the source and destination systems.
- Determine how the fields correspond with each other in terms of their values.
- Organize whenever time comes so that the integration can happen over time.

Benefits: It gives you a graphical representation for controlling all-integrated services, and it is good for different ways of making these connections.

5. Scripting Inclusion

Strategy: Makes distinctive integrations with the help of JavaScript.

Procedure:
- Formulate a script inclusion
- Compose JavaScript to get in touch with other systems.
- Utilize it in diverse sections of ServiceNow including the script inclusion.

Adaptability: Known to be very flexible but needs someone with programming skills.
