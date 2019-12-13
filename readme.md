### Robot Code Naming Conventions and General Pratices when Writing Code

#### General 

When naming variables, use snake_case  
When naming functions, use camelCase  
When naming classes, use UpperCamelCase
When naming constants, use ALL_CAPS_SNAKE_CASE  

Never create something that already exists.

Add descriptive comments to your code

Do not create long, unreadble chunks of code, unless there's literally no other way

Never use non-variablized numbers when calling functions

Store everything that's a number (all ports, ect) in variables to make them easy to change

Make sure that every created variable is or will be used

#### Github

Always create a new branch for your project

Add yourself to issues that you're working on to avoid confusion

Close issues after they've been solved

#### Commits:

Commit and push after every (WORKING) change

Always test your code before commiting it - it's your job to make sure your code works

Never push to master (VSCode won't let you do this anyway)

#### Robot-Specific

Name the drivetrain drivetype_drive  
Ex: omni_drive or arcade_drive

Name the controllers 'driver' (port 0) and 'operator' (port 1)

Name motors based on their position + type for individual (self.leftTalon, self.rightVictor),  
or just position for groups (self.left)
