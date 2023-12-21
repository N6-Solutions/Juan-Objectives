# Windows Server Configurations
## Purpose:
- To provide a standardized process for the configuration of Windows Servers.
## Scope:
- This SOP applies to all IT department employees who are tasked with the deployment of Windows Servers.
## Responsibilities:
- Management department: Notify IT of the required role of new Windows Servers to be deployed.
- IT department: Create, configure, and secure Windows Servers for required purposes.
- All Employees: Comply with AUP and security guidelines when accessing server resources.
## Prerequisites:
- Management notifies the IT department of new server requirements and details of use, and roles the server will have.
## Windows Server Configuration:
- IT department verifies the received information and initiates the Windows Server creation process.
- IT department plans the creation and deployment of the server.
- IT department updates necessary documentation such as topology reports. 
## Windows Server Configuration:
### Hardware Requirements
- This is the requirement for baseline windows servers based on documentation.
- Minimum storage requirements: 36 GB for the OS standard desktop edition. 
- Physical memory: 3x total RAM
- Roles (File and Storage share, DHCP, ect): 10 GB per
- Server updates: 10 GB  
### Additional requirements (depending on services)
- Active Directory, DNS, and certificate considerations.
- File sharing 
- User created data
- In total up to 160 GB in terms of practical implementation.
### Key Processor requirements:
- Minimum 1.4 Ghz
- 64 bit processor
- OS protection such as DEP, and SLAT. 
### Key Memory Requirements:
- Minimum RAM: 2 GB (this is baseline needs, more memory can be allocated for future needs).
## User Training:
- New employees will need to complete training on network security best practices.
- They are educated on ACL policies and AUP for server access.
## Granting Access:
- Management department will notify the IT department about employees that require server access.
- IT department will update permissions or create required OUs using AD DC for employees that needs access. 
- IT department will place employees that require server access in appropriate groups with appropriate permissions.
- IT department will provide new employees with their server network credentials in a secure manner.
## Monitoring:
- Server network monitored for any irregularities.
- Any suspicious activity is logged, reported, and investigated.
## References:
- Employee Onboarding Document
- Security Control Document
- Security Measures Guidelines
## Definitions:
- AUP: Acceptable Use Policy, is a document that outlines the acceptable ways in which a computer network or system may be used. It is a set of rules and guidelines that define the proper use of an organization's information technology resources by its employees.
- ACL: Access Control List, is a set of rules or entries that specify what actions are allowed or denied for a given user, system process, or group of users on a computer system or network.
- Permissions: Permissions refer to the rules or settings that dictate what actions users or system processes are allowed or denied.
- AD DC: Active Directory Domain Controller is a server that manages security authentication requests and enforces security policies within the Active Directory infrastructure.
- Windows Server: Windows Server is designed to operate on server hardware and provide essential services and roles for networking, communication, security, and data storage within an enterprise environment.  
Revision History:
Version 1.0 (Author: Juan Maldonado, Date: 12.20.2023)

