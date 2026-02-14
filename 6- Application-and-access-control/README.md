##  Scenario
The project team requested that as part of the non disclosure agreement, access to VitaScope-FD incident records should be restricted to only Service Desk and the Pilot Training Support group members but the asset tag field should be read only to all users except he product owner. But callers should be able to view their own incident in the employee center portal. 

As the system administrator, I will configure access to the VitaScope-FD incident records for only Service Desk and the Pilot Training Support group members and configure write access to the asset tag field for only the poroduct owner.  

## Objective
Configure access to the VitaScope-FD incident records for only Service Desk and the Pilot Training Support group members and configure write access to the asset tag field for only the poroduct owner.

## Tasks Completed
- Configure role for application menu and modules
- Configure role for Service Desk and the Pilot Training Support group
- Test visibility for group members
- Establish Access Control Rules for incident by hiding access at the table level
- Update Read, Write and Create access for role so group members can have those access
- Create new role for asset tag and configure Access Control Rules for Write
- Create a new Write access in ACL for hardware table that restrict only the Asset tag field (By adding the asset tag role to it)
- Create new group, updfate role and add product owner as member
- Verify access to edit access tag

## Result
Access to VitaScope-FD incident records has been restricted to only the Service Desk and Pilot Training Support group members. In addition, only thr product owner can edit the asset tag field on the form. 
