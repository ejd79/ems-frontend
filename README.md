# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh


# Steps to create project

- create project "ems-frontend":   
npm create vite@latest ems-frontend  

# Create React ListEmployeeComponent
- Create react functional component
- Prepare dummy data
- Write jsx code 
- Import component into App component
- Run and Test

# Let's work on style with....  

Bootstrap 5 :  
- container (https://getbootstrap.com/docs/5.0/layout/containers/)
- table (https://getbootstrap.com/docs/5.0/content/tables/)

# To connect to backend REST API:  
- Install Axios Library (npm install axios --save)
- Create EmployeeService.js file
- Write REST Client code to make REST API call using Axios API
- Change ListEmployeeComponent to Display Response of the REST API (List of Employees)
- Test the above changes  

# Adding Header and Footer  
- Create HeaderComponent (functional component)
- Import and use HeaderComponent in App component
- Create FooterComponent (functional component)
- Import and use FooterComponent in App component 

# Configure Routing  
- Install react-router-dom library (npm install reacct-router-dom --save)
- Configure routing in App Component
- Configure Route for ListEmployeeComponent
- Test Route for ListEmployeeComponent  

# Create React EmployeeComponent  
- Create React Functional Component - EmployeeComponent  
- Add "Add Employee" button in ListEmployeeComponent  
- Configure Route for EmployeeComponent  
- Test the above changes  

# Add employee form handling  
- Define state variables (firstName, lastName and Email) in EmployeeComponent using useState Hook  
- Design Add Employee Form using HTML and Bootstrap  
- Create JavaScript function to handle onClick Event (Form Submit)  
- Test React App (print form data in browser console)  

# Connect react to Add Employee REST API  
- In EmployeeService, write a code to call Add Employee REST API using axios  
- Change EmployeeComponent to call EmployeeService method  
- Navigate to List Employees Page After Form Submission Done  
- Test above changes  

# Add Validation to Form  
- Use the useState hook to initialize state variables that will hold validation errors  
- Write a validation function that check form data and returns validation errors  
- Validate form on submission  
- Display validation errors  
- Test above changes 







