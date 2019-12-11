### Robot Code Naming Conventions and General Pratice when Writing  Code

#### General 

When naming variables, use snake_case

When naming functions and classes, use camelCase

When naming constantes, use ALL_CAPS_SNAKE_CASE

Never create something that already exists.

Give descriptive comments

Do not create long, unreadble else-if chains

Never use non-variablized numbers in function calling

Put everything (all ports, ect) in variables

Actual use the created variables



#### Github

Allways create new branches for your projects

Commits:

Commit (and push) after every (WORKING) change

Allways test your code before commiting

Never push to master


#### Robot-Specific

Name the drivetrain drivetype_drive 

Ex: omni_drive or arcade_drive

Name the controllers 'driver' (port 0) and 'operator' (port 1)

Name motors based on their position + type for individual, just position for groups

Ex: self.left 
or: self.leftTalon
or: self.rightVictor


