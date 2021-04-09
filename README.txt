Workflow:

requirements.txt file:
- requirements file contains all packages used in MDA course (as of 4/9/2021; https://github.com/despiegj/goz39a.git) 
- Communicate in team meetings if a new package was added between meetings. 
- At the end of the project, trim down to packages that were actually utilized.

'protect' folder:
- Place files here that should not be changed by other team members between meetings. 

'work' folder:
- Files in 'work' can be changed by all team members between meetings.
- Branching is only done within 'work'.
- If deemed necessary, communicate/discuss/agree before merging contributions to a file in 'work'.

'production' folder:  
- During team meetings:
   1) Move intermediate results to 'production' (jupyter nbs, python scripts, etc.).
   2) Also, create copies of the intermediate results in 'work'.
   3) Copies of intermediate results in work are new starting position for the next week´s cycle of collaboration. 