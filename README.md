**Oracle Pluggable Database Assignment II**

*Student Information*

Name: RUGENZI PRINCE LEWIS.

Student ID:29074

Course: Database Development with PL/SQL (INSY 8311)



**Assignment Overview**

This assignment focuses on practical skills in Oracle Multitenant Architecture, specifically managing Pluggable Databases (PDBs). The tasks include creating and deleting PDBs, creating users inside a PDB, and documenting the process professionally.



**Oracle Environment Used**

* Oracle Database Version: Oracle 23ai
  
* Tool Used: SQL*Plus / Oracle SQL Developer
  
* Operating System: Windows



**Task 1 — Create a New Pluggable Database**

A new Pluggable Database was created following the required naming conventions.

*PDB Name*

le_pdb_29074

**Screenshot.**

<img width="614" height="85" alt="PLUG_CREATION (1)" src="https://github.com/user-attachments/assets/976bf4fb-51f5-48fe-bcf2-ce591b197ec4" />



 User Created Inside PDB

lewis_plsqlauca_29074

**Screenshot.**

<img width="439" height="89" alt="USER CREATION" src="https://github.com/user-attachments/assets/85d3799f-18a2-41a2-ae28-3bd867a6fdd9" />



The PDB was successfully created, opened, and verified. The user account was also created and will be used for future coursework.



## Task 2 — Create and Delete Temporary PDB.

A temporary PDB was created and then completely removed as required.

### Temporary PDB Name

le_to_delete_pdb_29074

**Screenshot.**

<img width="476" height="48" alt="DROP PDB" src="https://github.com/user-attachments/assets/eaaa2f2d-30df-41ef-ab32-32d215df2cdb" />


Steps completed:

* Created temporary PDB

* Verified its existence

* Deleted the PDB including data files

* Confirmed it no longer exists



## Task 3 — Oracle Enterprise Manager (OEM)

Oracle Enterprise Manager was successfully configured and accessed.

The dashboard displays:

* Oracle database environment
  
* Created PDBs
  
* User information

## Screenshots.

<img width="956" height="419" alt="OEM DASH1 (1)" src="https://github.com/user-attachments/assets/75903c69-9221-4e07-bdcc-c870f358f921" />



All required evidence screenshots are included in the *screenshots/* folder:

* PDB creation

* PDB open state

* User creation

* Temporary PDB creation and deletion

* OEM dashboard



## Challenges Faced

During the assignment, I encountered permission and container errors when creating the PDB.

### Solution

The issue was resolved by switching to the *CDB$ROOT container* and connecting as SYSDBA before running the commands.



##  Repository Information

Repository Name: oracle_pdb_ass_II_29074_lewis

Visibility: Public



##  Integrity Statement

I confirm that this assignment was completed individually through my own practical work and understanding. All commands were executed by me, and the documentation reflects my own learning process.



## Conclusion

This assignment strengthened my understanding of Oracle Multitenant Architecture, PDB lifecycle management, and professional documentation practices. The skills gained will support future PL/SQL development and database administration tasks.


