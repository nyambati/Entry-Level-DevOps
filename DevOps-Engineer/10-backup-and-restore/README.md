# Outcome 10 - Backup & Restore

Skill Description
-----------------
The Fellow understands the process of backing up data on a system in a frequent manner so as to be able to recover from data loss or system crashes



Outputs
-------
After attaining this skill, and as a demonstration of it, a fellow should be able to complete the following:

1. An exercise that covers the following operations:
  - Setting up recurring automatic backups of critical data (database, e.t.c) on a system
  - Setting up scripts to verify the backups to ensure it is valid and restorable
  - Setting up scripts to move the backup data to an external store (AWS S3)
  - Putting together a recovery plan to restore the data in the event of data loss


**Objectives**
--------------


## **Knowledge**

| Knowledge Unit   |      Studied      | Memorized |
|:-----------------|:-----------------:|:---------:|
| I can describe the following from memory: | | |
| The kind of data to be backed up on a system | [ ] | [ ] |
| How to identify existing backup/restore tools | [ ] | [ ] |
| How to restore backups to a system in the event of data loss | [ ] | [ ] |


----------------


## **Behaviors**

| Observable Behavior   |      Observed      | Mastered |
|:----------------------|:------------------:|:--------:|
| **Context:** When I setup a plan to backup data **Action:** I identify the critical data that should be backed up | [ ] | [ ] |
| **Context:** When I setup a plan to backup data **Action:** I set a recurring schedule at which the data should be backed up | [ ] | [ ] |
| **Context:** After I backup data on a system **Action:** I encrypt it so as not to expose user data | [ ] | [ ] |
| **Context:** After I backup data on a system **Action:** I move the backup to an external system for safekeeping | [ ] | [ ] |
| **Context:** After I move the backup to an external system for safekeeping **Action:** I delete the backup from the system to free up space | [ ] | [ ] |
| **Context:** Before I restore data on a system **Action:** I fetch the data from the remote store and place it on the machine | [ ] | [ ] |


--------------


## **Beliefs**

| Embodied Belief   |      Felt      | Demonstrated |
|:------------------|:--------------:|:------------:|
| System configuration and software should not be backed up as they can be replayed by the configuration management scripts | [ ] | [ ] |
| Backups should be of data only | [ ] | [ ] |
| Backups should be encrypted and stored in a secure manner so as not to expose user information if there is any | [ ] | [ ] |
| Backups are necessary to restore state in the event of system crash or data loss | [ ] | [ ] |