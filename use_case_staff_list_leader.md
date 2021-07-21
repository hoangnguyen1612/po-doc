# Use Case Access to Staff List with the Leader role 

## Prerequisites 
- Logged in: ttuan 

## Scenario 
### When
ttuan access to Staff List Page &nbsp;

### Then 
he can only see the list of staff in the group he is in charge of, that is the Ticket team. Because he only has Read/Write Same group/Same Team permission.
| Staff List | Action
| ---- | ---- |
| ngtan | [edit]() |
| nphong | [edit]() |
| clan | [edit]() |
| nlong | [edit]() |

he can also edit the staff info of ngtan,nphong, nlong and clan because has Write Same group/Same Team permission. 

## Reference 
[See more](d1_leaders_role_group.md)
