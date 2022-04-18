# CS305---Software-Security-

Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
-	In my role as a developer for Global Rain, I was given the task of implementing the most current and effective software security protocols for a financial consulting company called Artemis Financial. I was tasked with analyzing their software for security vulnerabilities using vulnerability checking tools, and then advising/implementing secure practices into their software.


What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
-	Part of our process in identifying security vulnerabilities was running dependency checks against their software. After doing this we were presented with a list of vulnerabilities. It was then my role to analyze the vulnerabilities and check for solutions, or, suppress the vulnerabilities as false-positives. I did well in this role by thoroughly researching these vulnerabilities and finding out if there existed patches that could be implemented to solve them. It is important to run dependency checks regularly to find out if a new vulnerability has been found and if there is a solution you can quickly implement. This process will help ensure that the code you are responsible for, maintains the best available software security measures. It’s important to regularly check and bolster the company’s software security in order to provide the most secure environment for the company. 


What about the process of working through the vulnerability assessment did you find challenging or helpful?
-	The vulnerability report provides a large amount of information about the vulnerabilities of the software you use it on. Understanding where to look and what everything means is very important. I found it useful my first time analyzing a report to take my time and research every detail that I didn’t understand. Once I had an understand of how to read the report, it was no longer challenging, just time consuming to evaluate each vulnerability and decide what action to take with it.


How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?
-	The client needed their program to run on a server. In order to provide this, there needs to be secure communication between the program and the server to ensure that the server trusts that the program is coming from the client and is not a malicious intruder. In order to verify this secure communication, I implemented an encrypted certificate, which allows the server to validate that the program is coming from the client. In the future I will definitely be using a dependency checker to evaluate security threats and I know that if I need to pass a program to a server, I will be needing to generate encrypted certificates.


How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?
-	One tool we used which verifies if an encryption was functional and secure is a checksum. By running a checksum we were able to see that our data was able to be encrypted when the program was executed. By running vulnerability checks before and after making changes to the code, you are able to see if new vulnerabilities appeared. 


What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?
-	I had never delved very far into cryptography before this course, but I have learned how important and useful it is so I will definitely keep it in my toolset when wanting to implement security features to programs in the future. 
-	The vulnerability report is a very useful tool when analyzing a program for security issues. I have used maven in the past but never analyzed security reports to such extent. I will definitely be using it in the future when wanting to ensure secure code.


Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?
-	If I were to showcase a piece of work that I felt I did well on it would be the Vulnerability Assessment Report that I completed for Project One and included in this repository. I felt that I was competent in running the report and finding security issues in the code. Additionally, I learned much more about the concept since submitting that project, so  I would be able to revisit it and complete it more competently. 
