# CODETECH-Task2
NAME: Mohammed Shajith khan F

COMPANY: CODTECH IT SOLUTIONS

ID: CT6WDS1876

DURATION: SEPTEMBER 30TH 2024 TO NOVEMBER 15TH 2024

MENTOR: NEELA SANTHOSH KUMAR

OVERVIEW OF THE PROJECT PROJECT:EMPLOYEE MANAGEMENT SYSTEM
Develop a database for managing employee records, including personal details, job positions, departments, and salarios. This project involves creating complex relationships and queries. Design tablos for employees, departments, and job positions. Write SQL queries to manage employeo records and departmental information.

KEY ACTIVITES: 

1.Schema Structure:

The schema effectively separates departments, roles, and employees, maintaining clarity in role-specific salaries and departmental associations.
Consider adding a date_of_birth or date_of_joining field in employees for further analysis, like tracking tenure.

2.Employee List with Departments and Roles:

The query to list employees with their department and role details is concise. It could be extended to include sorting (e.g., by hire date or salary) for ordered outputs.

3.Department-Specific Employee List:

The query targeting employees in a specific department is efficient. You might consider parameterizing the department name to make it more adaptable for various departments.

4.Employee Count by Department:

This count query provides a quick summary of employee distribution across departments. If any department lacks employees, this query will still display it, thanks to the LEFT JOIN.

5.Filtering High-Salary Employees:

The query listing employees with salaries above a threshold is valuable for salary analysis. To refine it further, consider including additional fields like role_name or department_name for more context.

6.Updating Employee Roles:

This role update query is functional. You could extend it with a subquery to fetch role IDs by name, making it adaptable without needing to know specific role IDs.

7.Deleting Employee Records:

This deletion query is straightforward. It’s a good practice to handle such operations carefully, especially if cascading deletions are enabled.

Output:

![6e89c05b-1a15-4b64-a834-f20113a9e27d](https://github.com/user-attachments/assets/c0139903-3597-4082-8c29-8de3acfd0d52)
TABLE employee,department,roles

![3a9b94a3-d910-45e1-8731-ba5563825e02](https://github.com/user-attachments/assets/74c6121b-571a-48cd-a786-88ff095894a6)
list all employees with their department and role

![114cef3a-145d-4b6c-be68-dc847957702b](https://github.com/user-attachments/assets/f89af464-adf1-488e-a661-f4d22bacba0f)
get employees with salary above 65,000$

![6d63dc44-b576-43fd-9d7e-4c0c47cc7ceb](https://github.com/user-attachments/assets/abc7100f-d45b-48bf-8969-5beadb3debac)
find employees in a specific department engineering

![b126fd8d-9bf4-4c68-90e0-22bd80e92817](https://github.com/user-attachments/assets/f6c1dce9-f3b7-48d0-8bc4-65f2207ca241)
count employees in each department

![76e0dbd6-931b-461f-bbc7-3d07632793d1](https://github.com/user-attachments/assets/0aa387ce-f968-4aca-92a4-cb28da44b3a3)
update a employees role

![9103886c-411f-46d3-bd05-f3a0cd123d87](https://github.com/user-attachments/assets/4eff1ecf-caa5-4f99-8a28-06dd9a849641)
to delete an employee with employee number three

TECHNOLOGY USED: Mysql
