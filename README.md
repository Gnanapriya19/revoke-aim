AIM: 
To implement DCL Commands to set and revoke privileges. 
PROCEDURE: 
Data control language (DCL) is used to access the stored data. It is mainly used for revoke and to grant the user the required access to a database. In the database, this language does not have the feature of rollback. 
It is a part of the structured query language (SQL). 
It helps in controlling access to information stored in a database. It complements the data manipulation language (DML) and the data definition language (DDL). 
It is the simplest among three commands. 
It provides the administrators, to remove and set database permissions to desired users as needed. 
These commands are employed to grant, remove and deny permissions to users for retrieving and manipulating a database. 
GRANT Command 
It is employed to grant a privilege to a user. GRANT command allows specified users to perform specified tasks 
Syntax 
GRANT privilege_name on objectname to user; Here, privilege names are SELECT,UPDATE,DELETE,INSERT,ALTER,ALL objectname is table name 
user is the name of the user to whom we grant privileges 
REVOKE Command 
It is employed to remove a privilege from a user. REVOKE helps the owner to cancel previously granted permissions. 
Syntax 
 REVOKE privilege_name on objectname from user; Here, privilege names are SELECT,UPDATE,DELETE,INSERT,ALTER,ALL 
object name is table name user is the name of the user whose privileges are removing 
 
