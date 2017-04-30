# qube-task2
Qube Code Challenge - Task 2

----------


**Bash script for below code challenge**

 - Automate the process of stop

Automate the process of stop to a group of instances (based on tags). Ensure that there is no user logged into the servers, and CPU usage is idle for the particular period of time before the stop. The idle period and tag will be passed in as the arguments.

    usage: autostop <Tag name> < idle period>

For example:

    autostop <development> 30

If the current time is 7 PM, the script needs to check the idle development instances in the last 30 minutes( means 6.30 PM to 7 PM) and no users logged into the instances before stop. Don’t set up permanent cloudwatch alarm to stop the instances. The script needs to run on-demand for stopping the instances.
