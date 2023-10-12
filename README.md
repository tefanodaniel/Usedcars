# Usedcars
A fun project to learn more about databases and web interfaces. **Currently in rough re-development (not available for install).**

- Main site can be found as `phase_e.html`.
- DB connection created in `open.php`. \*Conf file will be removed later*    
- SQL procedures can be found in `phase_e_procedures.sql`.  
- Original (cleaned) data files for database can be found in `dbase_setup/`. 

## Working design sketch
![the usedcars.com dashboard](https://github.com/tefanodaniel/Usedcars/blob/main/my%20idea%20for%20web%20layout.png)

## For future installations
Web site currently hosted by a local [Apache](https://httpd.apache.org/) server with [PHP](https://www.php.net/) 8.2 installed and configured.

Setup for database (scripts to execute to setup MariaDB database instance):  
- Tables: `dbase_setup/setup.sql`  
- Stored procedures: `phase_e_procedures.sql`
