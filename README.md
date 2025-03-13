**M2Project Installation Guide**

**Required Software & Tools:**
XAMPP (to run Apache and MySQL servers)
Node.js (to run the server)
Browser (e.g., Chrome, Firefox, etc.)

**Step-by-Step Instructions**
**1. Install XAMPP:**
- Download XAMPP from the official XAMPP website.
- Follow the installation instructions to complete the setup.
**2. Install Node.js:**
- Download Node.js from the official Node.js website.
- Follow the installation instructions to complete the setup.
**3. Download M2Project System Files:**
- Download the M2Project system.rar file.
- Extract the .rar file using any file extraction software (e.g., WinRAR, 7-Zip).
**4. Place the Folder:**
- Once extracted, place the project folder in your Local Disk (C:) for easy access.
    Example path: C:\M2Project.
**5. Configure XAMPP:**
- Open XAMPP.
- Start Apache by clicking the Start button next to it. This will start the Apache server.
- Start MySQL by clicking the Start button next to MySQL. This will start the MySQL server.
- Click Admin to open phpMyAdmin in your browser.
**6. Create Database:**
- In phpMyAdmin, click the Databases tab.
- Create a new database named cirva_database.
**7. Import SQL File:**
- In phpMyAdmin, after selecting the newly created cirva_database, click the Import tab.
- Browse to the cirva_database.sql file in the M2Project folder and import it.
**8. Start the Server:**
- Navigate to the M2Project folder (e.g., C:\M2Project).
-In the folder path bar, type CMD and press Enter to open the command prompt directly in that folder.
- In the command prompt, type the following command:
    node server.js
This will start the server for your project.
**9. Access the Project in Browser:**
- Open your browser (Chrome, Firefox, etc.).
- In the address bar, type localhost:3000 and press Enter.
- This should open the M2Project system in your browser.

**Troubleshooting Tips**
If you encounter any issues during installation or execution, here are some common solutions:

**1. Apache or MySQL Not Starting in XAMPP:**
- Check if another application (like Skype) is using the same port (80 for Apache or 3306 for MySQL).
- You can change the port settings in XAMPP if needed.
**2. node server.js Command Not Working:**
- Ensure you have installed Node.js correctly.
- Make sure you’re in the correct folder (C:\M2Project) in your command prompt.
- Run npm install in the folder to install all necessary dependencies before running node server.js.
**3. Browser Not Showing Project:**
- Ensure Apache and MySQL are both running in XAMPP.
- Double-check the server URL (localhost:3000).
**4. Database Issues:**
- If you have trouble with the database import, verify that the database cirva_database is created in phpMyAdmin and try importing the SQL file again.
- Check for any errors in the import log in phpMyAdmin.


**Contact Information:**
If you continue to face issues or need further assistance, feel free to reach out to any of the following programmers:

jaAlbinda@mcm.edu.ph
ajCapricho@mcm.edu.ph
acDelaCruz@mcm.edu.ph
