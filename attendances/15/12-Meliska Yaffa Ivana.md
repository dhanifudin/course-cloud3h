### High Availability on Cloud Environment

a. Everyone expects their infrastructure to be available all the time
b. A 100% guaranteed availability of an infrastructure is impossible

## 1. Calculating availability
Availability can neither be calculated, nor guaranteed upfront
It can only be reported on afterwards, when a system has run for some years
Over the years, much knowledge and experience is gained on how to design high available systems
Failover
Redundancy
Structured programming
Avoiding Single Points of Failures (SPOFs)
Implementing systems management
The availability of a system is usually expressed as a percentage of uptime in a given time period
Usually one year or one month

## 2. Sources of unavailability - human errors
80% of outages impacting mission-critical services is caused by people and process issues 
Examples:
Performing a test in the production environment
Switching off the wrong component for repair
Swapping a good working disk in a RAID set instead of the defective one
Restoring the wrong backup tape to production
Accidentally removing files
Mail folders, configuration files
Accidentally removing database entries
Drop table x instead of drop table y

## 3. Sources of unavailability - software bugs
Because of the complexity of most software it is nearly impossible (and very costly) to create bug-free software
Application software bugs can stop an entire system
Operating systems are software too
Operating systems containing bugs can lead to corrupted file systems, network failures, or other sources of unavailability

## 4. Sources of unavailability - planned maintenance
Sometimes needed to perform systems management tasks:
Upgrading hardware or software
Implementing software changes
Migrating data
Creation of backups
Should only be performed on parts of the infrastructure where other parts keep serving clients
During planned maintenance the system is more vulnerable to downtime than under normal circumstances
A temporary SPOF could be introduced
Systems managers could make mistakes

## 5. Sources of unavailability - physical defects
Everything breaks down eventually
Mechanical parts are most likely to break first
Examples:
Fans for cooling equipment usually break because of dust in the bearings
Disk drives contain moving parts 
Tapes are very vulnerable to defects as the tape is spun on and off the reels all the time
Tape drives contain very sensitive pieces of mechanics that can break easily

## 6. Sources of unavailability - environmental issues
Environmental issues can cause downtime:
Failing facilities
Power
Cooling
Disasters
Fire
Earthquakes
Flooding 

## 7. Sources of unavailability - complexity of the infrastructure
Adding more components to an overall system design can undermine high availability
Even if the extra components are implemented to achieve high availability
Complex systems
Have more potential points of failure
Are more difficult to implement correctly
Are harder to manage
Sometimes it is better to just have an extra spare system in the closet than to use complex redundant systems










