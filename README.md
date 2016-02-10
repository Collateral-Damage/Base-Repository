# Base-Repository
Model repository for all future repos.
Each repo should have a folder for Client and Server files. They should be named (Pack Name) Client and (Pack Name) Server respectively. 

1. Folders should contain ONLY what is necessary to the end user. Mods, Configs, Scripts, Template, ETC.
2. Server files should contain all forge libraries and jars necessary to run the server.
3. Server files do **NOT** include server properties, EULA, whitelist, ETC. These are generated when the server jar is run.
4. Server files can contain .bat or .sh ServerStart files for java parameters, if desired.
5. Server file should contain a document that lists the mods that are Client-Side only! Client-Side only mods are mods that will crash the server on start-up and must be removed before running the server. These mods should already be removed by you first before the update, however this list is so that players are aware just in case we mess up or they change the mods list.

This section of the README above can be replaced with the Repository name and pack information once established. These guidelines still apply.

#Issue Submission
READ THIS BEFORE SUBMITTING AN ISSUE:

1. Tag the issue title with HOW the issue should be viewed. Bugs should be tagged with [bug], proposals should be tagged with [enhancement]. Use some sort of bracket system. 
2. Crash reports should be in some type of paste accessible via link. DO **NOT** post the body your crash report as your issue. Unless it is exported from YAMPST, your issue will be immediately closed. Provide additional information on what you did to cause the crash and if it is easily reproducible. 
3. Be specific on HOW you produced your bug or WHY you are proposing an enhancement. 
4. Issue Submission should follow general documentation guidelines found below.

#Documentation
All commits and pull requests need to follow these guidelines upon submit:

1. The Summary indicates the pack version that your commit is GOING to affect. Ex: If the pack is publicly on version 1.0.0, your update will most likely be working towards 1.0.1 unless otherwise expected.
2. The description indicates the major purpose of your update. Did you update some mods? List them. Change any configs? List what you changed and why. If your commit addresses a specific issue or pull request, mention it with the #(number of the PR or issue) and how your commit changes the way we look at that issue. Did you fix it? Did you simply provide a work around?
3. Pull Requests should have an intuitive title and adequate documentation of all proposed changes. Pull Requests follow the same rules above. The more thorough the better!

# Script Structure
All script file(s) created should meet the following conditions:

1. Recipes are grouped by type. Types should be logically named and seperated. Ex: "Armor Recipe Changes" is okay, "Group 1" is not okay.
2. All groups are properly commented. It should be evident what the purpose of the script was. Are you removing or adding a new recipe? Are you using a unique form of crafting? PLEASE BE SPECIFIC!
3. The file is easily readable to anybody. There should be proper white space, indentation and seperation of group blocks. 

