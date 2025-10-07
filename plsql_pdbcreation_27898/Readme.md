Names: GATOYA CYUZUZO Grace
Student_id: 27898
Course name: PLSQL

ASSIGNMENT 2 REPORT: PDB CREATION, DELETION AND OEM

Task 1: Creation of a new PDB

	PDB  name: gr_pdb_27898
        PDB username: grace_plsqlauca_27898(with it's password)
Screenshots:[pdb_creation scr](screenshots/pdb_creation scr.png),[user_creation scr](screenshots/user_creation scr.png)

Task 2: Create and delete a PDB

	PDB name: gr_to_delete_pdb_27898
creation screenshot:[pdb_delete_creationscr](screenshots/pdb_delete_creationscr.png)
		    [gr_to_delete_pdb_27898](screenshots/gr_to_delete_pdb_27898.png)

deletion screenshot:[delete_pdb scr](screenshots/delete_pdb scr.png)
		    [deleting_pdb scr](screenshots/deleting_pdb scr.png)


Task 3: ORACLE ENTERPRISE MANAGER

Configuring Oracle database manager

screenhshot of the OEM dashboard:[OEM_Dashboard_scr](screenshots/OEM_Dashboard_scr.png)


PDB acces in SQL DEVELOPER
	#Opened sql developer
	#Created a connection(plsql) with username (grace_plsqlauca_27898) and with the service name (gr_pdb_27898)
        Purpose: to show the PDB created and the user name in SQLDEVELOPER since it failed to be shown in teh OEM

screenshot:[userand pdb](screenshots/userand pdb.png)


ISSUES ENCOUNTERED AND THE SOLUTIONS MADE

Issue							solution
PDB user could not log in OEM/DB Express		used SQLDEVELOPER to access the PDB user since the OEM/DB Express does not allow
New PDB not showing in OEM				Verified listener registration and PDB service; still not visible due to XE limitation


CONCLUSION

#Successfully created a PDB and a user account.

#Practiced creating and deleting a temporary PDB.

#Verified PDB access using SQL Developer when OEM could not display it.

#Captured all required screenshots and documented steps and troubleshooting.



