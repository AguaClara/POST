# POST Issue Update for Week of 3/4

#### 1. [Issue #1, 3/4] Extract all past data from ODK Aggregate
    a. 3/10 - EXTENDED
    b. gap75
       i.[gap75, 3/5] - Tried to use the export function in ODK Aggregate to export all the data into a CSV file. Unfortunately, the export experienced an error halfway through the operation due to the fact that the Aggregate quota was being surpassed. Due to the fact that the quota was exceeded, I was locked out of the Aggregate server for 12 hours.
       ii. [gap75, 3/6] - An online web search indicated that ODK Briefcase may be a way to get around the quota limit. Spent most of the time learning how to work with ODK Briefcase and dealing with connection errors in the data pull request. 
       iii. [gap75, 3/7] - Found the credentials to connect ODK Briefcase to Aggregate, to deal with the connection errors. Unfortunately, Briefcase still falls victim to the data quota, so I will have to investigate a more creative way to get the data out of ODK. 
#### 2. [Issue #2, 3/4] Running an automatic email python script remotely from a server
    a. 3/10 - EXTENDED
    b. rrr225
       i. [rrr225, 3/5]Learning AWS, which is the server option I’ll try to have the python script run
       ii. [rrr225, 3/6] I was able to create and setup an AWS server that will then run the script. The script still doesn’t run yet, just setup is done
       iii. [rrr225, 3/7]Added the script to the server, and been bug fixing to make sure it can work 
#### 3. [Issue #3, 3/ 4]Displaying the data table on website
    a. 3/10-EXTENDED
    b. yw299
       i. [yw299, 3/5] Successfully removed the extra download section from the navigation bar
       ii. [yw299, 3/7]Tried to add a new component called table and started to implement code that displays the table. Haven’t figured out how to do it yet.

#### 4. [Issue #4, 3/4] Allow POST users to skip a question on the form (ODK)
    a. 3/10 - EXTENDED
    b. rt457
       i. [rt457, 3/5] Went through current ODK form to identify questions to update
       ii. [rt457, 3/6] Researched and implemented skip logic to appropriate questions on the platform
       iii. [rt457, 3/7] Continued to make progress on the ODK form and tried to rearrange questions for efficiency and relevance
#### 5. [Issue #5, 3/4] Automatic email script
    a. 3/10 - CLOSED
    b. nb378
       i. [nb378, 3/5]  Got data out of firebase, started parsing 
       ii. [nb378, 3/6] Got data into necessary data structures
       iii. [nb378, 3/7] Finished scripts for creating graphs for specific plants
