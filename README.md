# Logistic Management System (LMS)

This project was designed and deployed for a small company (20-40 employees) which intended to grow the business and connect Microsoft SharePoint (which serves the data of customers, previous projects, assets, logistics, parts, modes, shifts, employees, availibities, etc ) to a new infrastructure for making the full data accessible by several admin accounts and employees (with different level of access) on-demand. <br>
LMS was designed to be responsible for the future demands of the company on managing assets (warehouse, logistics and human resources) as well as adding the security and the connection of the server to the Microsoft Share Point (MSP) of the company which hosts the additional details of the projects and assets. Put simply, Logistic, warehouse and employee management systems were all included in this LMS project. According to the business constraints and non-relational nature of the MSP database, NDBMS was used by integrating MongoDB and its connection to a cloud-based DBMS. Responsive front-end and complex back-end engines were designed and implemented to address several key features as mentioned below. MEAN Stack technology (MongoDB, Express, Angular and Node.js) was employed for implementing the architectural design and DBs.
<ul>
  <li>Authentication and authorization as well as user validation</li>
  <li>Incorporating MVC for the front-end based on HTML5 and AngularJs for structuring and presenting contents</li>
  <li>Several engines in the back-end</li>
  <li>Heartbeat connection with MSP for the build-to-build upgrade on the server and DBs</li>
  <li>Encrypted communication between front and back-ends using AES 256</li>
  <li>Clearing up the server's catch occationally to increase the service efficiencies</li> 
  <li>Admins and employees (depending on their level of access) can add, edit, update, search and delete logistics, absences, parts of machines, availibities of employees depending on their skills for specific tasks on specific date, set for specific shift and availbility of machine</li>
  <li>Increasing efficiencies on processing orders and demands and transferring quick service to customers</li>
  <li>presenting two sets of calendars; (a) employees-dates, filled by the logistics, warehous, project data, (b) logistic-date, filled by employee, project, and warehouse data</li>
</ul>
