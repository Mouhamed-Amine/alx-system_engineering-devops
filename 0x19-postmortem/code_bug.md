![PostMortem](./post-mortem.jpg)
Issue Summary
After Delivering a scrapping script to one of my clients,A day after, i started recieving on my inbox 2 emails telling me that the " scrapping code didn't work " and i was confused since i described the following prepartion plan before execution.
Then the client pointed not on code running but something in his environement that was ruined by him but he just wanted me to take it off by refering to my code as a bug. I clone the code again and checked the problems he is having and tried to renew the script to automate and update dependencies that is missing in his computer.
The Maintenance were from 8:00 AM GMT+1 to 8:50 AM GMT+1.  

Timeline
11-08-2024 8:00 AM GMT+1 -  A customer Refers to the Bugs and dependencies issues.
11-08-2024 8:15 AM GMT+1  - I tried on fresh new machine and experienced the same issues the client reported.
11-08-2024 8:20 AM GMT+1 - I investigated the script and run it after few tweaks .
11-08-2024 8:30 AM GMT+1 - I wrote new dependencies needed to him and updated the README.md file.
11-08-2024 8:40 AM GMT+1 - Test it on my fresh machine and it works like a butter.
11-08-2024 8:50 AM GMT+1 - The client reported that his code works and no bugs are reported.


Root Cause And Resolution
Some of the commands to execute and install dependencies were deprecated ! so i had to change it to newer one from official docs

Corrective And Preventative Measures
- Need to run ubuntu commands on Latest
- Release a test version to run it on different machines

