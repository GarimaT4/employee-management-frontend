# Employee Management System (Frontend)

This is a simple web-based Employee Management System built using **HTML, CSS, JavaScript (jQuery), DataTables**, and **AJAX**. It interacts with a backend API hosted at `https://dfccil-api.azurewebsites.net/` to perform CRUD operations on **Employees, Departments, and Designations**.

## **Features**

- **Employee Management**
  - View all employees in a searchable, paginated DataTable.
  - Add a new employee with details like code, name, department, designation, salary, and profile photo.
  - Edit employee details and update the database using the API.
  - Display employee status as **Active/Inactive** with color indicators.
  - Default photo `photoicon.jpg` is shown when no photo is uploaded.

- **Department & Designation Management**
  - Separate pages to view, add, and edit departments and designations.
  - Status management for departments and designations.

- **Data Export**
  - Export table data as **CSV, Excel, PDF**, or **Copy to Clipboard** using DataTables buttons.

- **Responsive Design**
  - Fully responsive layout using simple CSS.
  - User-friendly modals for Add/Edit forms.

## **Tech Stack**

**Frontend:**
- HTML5, CSS3, JavaScript
- jQuery (AJAX for API calls)
- DataTables (for enhanced table functionalities)
- Moment.js (for date formatting)

**Backend (API):**
- ASP.NET Web API (Hosted on Azure)
- MS SQL Server (Database)

### Live Demo
[Click here to view the live site](https://garimat4.github.io/employee-management-frontend/)
