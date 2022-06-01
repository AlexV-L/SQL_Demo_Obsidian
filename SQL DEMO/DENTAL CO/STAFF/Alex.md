# STAFF DATA
type:: Staff
status:: Unassigned

# PATIENT INFORMATION
	Name:: Alex
	Address:: 750 Orchard Dr
	Phone:: 456-880-0643
	Insurance:: Pro Care

# ASSIGNED OPERATIONS
```dataview
TABLE Ongoing_Treatment AS "Ongoing Treatment",Appointment_Date, Time
WHERE Appointed_Staff= "Alex"
```
## APPOINTMENTS
#### Treatment:: Implant
	Appointment_Date:: NONE
	Time:: NONE
	Appointed_Staff:: NONE