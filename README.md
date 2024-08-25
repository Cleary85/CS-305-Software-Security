# CS-305-Software-Security
Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
Artemis Financial is a banking company that served clients both domestically and internationally, and they were trying to implement a web based interface for thier clients and required
consultation on improving the overall security posture of thier applications and code to better protect both business and customer data

What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
I was able to effectively test and identify vulnerabilities that were present in the underlying dependencies that were not directly coded by Artemis. Being able to sucurely code and preset an 
application is vital to proper functioning and prevents unexpected behavior that causes a server, application, service to become unreliable or unuseable. Financial data is vital to everyone and 
provides a statement of trust and responsibility that Artemis will need if it expects to maintain any customer base.

Which part of the vulnerability assessment was challenging or helpful to you?
The most challenging portion of the assessment was determining what vulnerabilities were applicable or at what level of severity they presented. Many of the vulnerabilities were tried to specific
processes or tasks with which I was not able to determine if there were other underlying peices of software that used that function or service. An example would be a .yaml parsing vulnerability. For
most of the outward facing connections, I would not expect a .yaml file to be passed for a banking application but could not neccessarily rule out the possibility nuy with a better idea of the
backend operations of the application, I would be able to confidently assess the level of risk from the vulnerability.

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
Increases to the layers of security included adding vulnerability scanning, throurough code reviews, and regression testing when new code was added. There are a number of tools that can be used to 
assess vulnerabilities. Mitigation become dependent on level of risk and option available for mitigation. While in the .yaml vulnerability listed above, if there is nothing in the underlying code
that utilizes .yaml files for operation, proper input validation would be appropriate to secure the risk, where if .yaml files are used, updating the underlying dependency or refactoring the code in
use to prevent the specific vulnerability might be more appropriate.

How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
In a phrase, regression testing. Revalidating security is very important to maintain a robust security posture and that means that retesting and rereviewing the application after updates to the code 
and dependencies is required in order to rule out the addition of new vulnerabilities when changes are made to the code base.

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
Multiple rounds of code review was especially helpful for me, as staring at a wall of code can be very taxing, both visually and mentally, and coming back to revisit the code can help maintain a 
fresh set of eyes and prespectives that enable a more complete review of the code

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
The thing that stands out to me that I would highlight from this assignment was the thourough wya in which the assessment was conducted. While no one is perfect, ensuring that when a security 
review is conducted, that review is as complete and rigerous as possible. This prevents potential surface area for exploit and helps eliminate lines of effort down the road that might be needed to 
correct a vulnerability that has become integral to the operation of the code base and prevent major refactoring of the code base to remove the vulnerability and maintain proper function of the 
application.
