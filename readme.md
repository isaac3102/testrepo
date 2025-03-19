# Group 46 – Chat Application
Chat application written in Python using socket programming.

## Features 
Our chat application features:
-	Unique usernames
-	Multiple user connectivity
-	Global chat across all users
-	Private messaging between all users
-	Breakout rooms

## Usage
 1. Execute`server. py`in the background.
 2. Clients will execute`client. py`in command prompt to begin connection to the chat server.
 3. Client will be prompted to enter a username and once successful, they will be able to access the chat server.

### General Commands	
This section lists general commands for base chat features.  
@public
> Sends a message to **all** users currently connected to the chat server.
```
@public <message>
```

@names
> Lists the usernames of **all** users currently connected to the chat server.
```
@names
```

@<username>
> Sends a **private** message to indicated user.
```
@<username> <message>
```

@help
> Lists all available commands to the user.
```
@help
```

@quit
> Disconnects the user from the chat server.
```
@quit
```

@history
> Retrieves the user’s chat history.
Syntax:
```
@history
```

### Group Commands
Commands for group management.  

@groups
> List **all** groups that the user is in.
```
@groups
```

@group set
> Creates a group with the given group name and usernames.
```
@group set <group_name> <usernames>
```
> Usernames should be separated with a space.

@group send
> Sends a message to the specified group
```
@group send <group_name> <message>
```

@group list 
> Lists all members and admin of the specified group
```
@group list <group_name>
```

@group leave
> Leaves the specified group
```
@group leave <group_name>
```

@group delete
> Deletes the specified group
```
@group delete <group_name>
```

@group add
> Adds a user to the indicated group  
> (Admin only command)
```
@group add <group_name> <username>
```

@group kick
> Kicks a user from the specified group  
> Admin only command
```
@group kick <username> <group_name>
```



| Member Name | SiT ID | UofG ID | Email |
| --- | --- | --- | --- |
| Lee Puay Ki Triona | 2403478 | 3070573L | [SIT](2403478@sit.singaporetech.edu.sg) [UofG](3070573L@student.gla.ac.uk) |
| Daniel Soong Jia Kang | 2403358 | 3070568S | [SIT](2403358@sit.singaporetech.edu.sg) [UofG](3070568S@student.gla.ac.uk) |
| Teo Zhi Kai | 2401566 | 3070661T | [SIT](2401566@sit.singaporetech.edu.sg) [UofG](3070661T@student.gla.ac.uk) |
| Lai Yueyin Shyann | 2402456 | 3070689L | [SIT](2402456@sit.singaporetech.edu.sg) [UofG](3070689L@student.gla.ac.uk) |
 
| Isaac Lee Junqian | 2401144 | 3070635L | [SIT](2401144@sit.singaporetech.edu.sg) [UofG](3070635L@student.gla.ac.uk) |


