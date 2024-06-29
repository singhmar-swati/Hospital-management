# Hospital Management System


## Description-
   Description
This project addresses the traditional challenges of hospital management by replacing paper-based systems with a digital solution. The system provides separate user accounts for doctors and staff, streamlines patient data management, and tracks previous visits with a single click. Developed in Java with a MySQL backend, it uses SpringMVC and Hibernate frameworks for platform independence, high performance, and security. Features include easy employee management and PDF generation of prescriptions.

### 1. Front end Technologies:
  - HTML
  - CSS
  - Bootstrap
  - JavaScript
  
### 2. Back end Technologies:
  - SpringMVC 
  - Hibernate
  
### 3. Database:
  - MySQL
  
### 4. Project management tool:
  - Maven
  
### 5. Webserver:
  - Apache Tomcat
  

## Issues that proposed system overcomes-
   - It is digital system rather than paper based.
   - Inappropriate data keeping (receptionist used register for patients entry and doctor used prescription pad).
   - Time wastage in data storage and retrieval.
   - Human error possibility in maintainance.
   - Patient's were unable to understand prescriptions due to handwriting issue.
   - Durability issues (data may lost if prescriptions goes missing).


## Features-
  1. Doctor module:
      - Seperate accounts for doctors
      - Each patients previous visits history is easily to access.
      - Doctor can generate prescription and it will be automatically sent to receptionist.
      - Doctor can remove patient from OPD queue.
      
  2. Receptionist module:
      - Register/add new patient's info.
      - Modify patients personal details
      - Search existing patient by name/ mobile no./ PID/ aadhar no.
      - Remove patient from OPD queue.
      - Take print of prescriptions.
      
  3. Administrator module:
      - Add new employee for following roles,
                      i) Doctor
                     ii) Receptionist
                    iii) Admin (another one)
      - Remove/edit existing employee. 
      - Displays currently active employees in system.
      
  4. Password Encryption:
      - *_Bcrypt Encoding_* is used for password encryption. Bcrypt is a password hashing function designed by Niels Provos and David Mazières. It is based on the Blowfish cipher. Bcrypt uses adaptive hash algorithm to store password. BCrypt internally generates a random salt while encoding passwords and hence it is obvious to get different encoded results for the same string. But one common thing is that everytime it generates a String of length 60.


