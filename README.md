# CS-305-Software-Security

**Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?**
Artemis Financial is a banking company that wanted me to ensure that their web browser application would be secure for their users. Artemis Financial wanted to guarantee that its users would be able to access their accounts without the risk of hackers gaining their personal information. 

**What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?**
One thing I did well when I found my client's software security vulnerabilities was analyzing ways to mitigate them. I found research on what hackers do to exploit systems very interesting and used the knowledge I accumulated to decide what was important to focus on when reading dependency reports and scouring the system for anything that seemed potentially susceptible. Coding securely is important because even little things such as lack of input validation or character limits can be easily abused by the most minor of hackers. Software security overall increases the trust users have in a company and the more invulnerable a software is to attack, the more likely users will want to use it. 

**Which part of the vulnerability assessment was challenging or helpful to you?**
One part that was challenging about the vulnerability assessment was figuring out what constitutes a "false positive." It took me some time to discern between a genuine dependency and something that does not truly apply to our system. I did plenty of research on how other people find false positives in their dependency reports and read Maven's information about false positives as well. This eventually meant I figured out how to tell if a false positive had been flagged, and can now decide what is truly a concern for the program. 

**How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?**
I increased layers of security by installing plug-ins that check for dependency and ensuring existing plug-ins were up to date. In the future, I would use these same plug-ins and thoroughly read the vulnerability reports to determine which dependencies should be given special focus. 

**How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?**
I made certain the code and software applications were functional and secure by deploying the website and ensuring that the code had switched my website from an HTTP connection to HTTPS. I ensured I didn't introduce any new vulnerabilities by running another dependency check and watching to see if anything new had popped up. 

**What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?**
Resources, tools, and practices I used that may be helpful in the future include the Maven Dependency check and the tutorials I followed that taught me how to read the reports and sift through the false positives. I would also include the resources that taught me how to find commonly overlooked areas of vulnerability so I can ensure that I catch them before my code is deployed. 

**Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?**
I would show them how I successfully generated a CA and deployed a browser with an HTTPS connection without introducing any new vulnerabilities to my code. I would also show them how many areas of vulnerability I discovered just by reading through the code myself, even if at that moment I could not work them out. 
