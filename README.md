# MaintenanceMonitor
Implements red and green Monitor to show current status. 
We will implement a project which takes in a number and checks if the downtime is still within our SLA. 
If within SLA a green monitor will appear on the webpage.
If not within SLA a red monitor will appear on the webpage.

We are a small hydro-power electricity supplier near Vienna. 
Our customers expect electricity around the clock with a service level agreement of 99.95%. 
This means that the maximum outage of 21 minutes and 54 seconds(monthly in sum) is tolerated. It is easy to derive that service times are very important to us. 
Huge monitors were installed that should show
•a green monitor in case everything looks fine and
•a red monitor in case of problems.
All monitors show the same content: a maximized website.