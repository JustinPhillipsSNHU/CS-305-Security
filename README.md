# CS-305-Security

#    Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
Artemis Financial was a financial institution looking to modernize accessibility for its clients by creating a web application. Their concerns for me to address were revolving around the cybersecurity elements of this application; The specific work requested was to secure the sensitive information the server must interface with, including financial and identity information. 

#    What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
I believe that my attention to detail while reviewing my client's outdated dependencies was great, and I also believe I implemented my SHA-2 and RSA encryption algorithms well. I would say that understanding the distinctive roles of different encryption and hashing techniques was something I performed well, because often times security needs depend on the context and application case. It is crucial to code securely to secure foundational cybersecurity advantages in an ecosystem full of eager, experienced, opportunistic attackers. Integrating cybersecurity into every stage of application development plays a major role in the reputation of the app and company, and is a long term investment into maintaining security and the customer trust that comes along with it. Failing to do so can be profoundly punishing, such as many consumers being turned off your services indefinitely.

#    Which part of the vulnerability assessment was challenging or helpful to you?
I found the Owasp Dependency checker, and in general the practice with Java and the .xml files, to be helpful. Something I found very helpful beyond the hands on practice was the dependency checker's thorough analysis, which saved me a ton of time with hands-on work. Something personally handy about the Owasp dependency checker is that I don't have a meaningful background in Java beyond school. Consequently, having a library explained to me through descriptions of it and its history, especially with bugs and vulnerabilities, helps me become acclimated to the Java community and the libraries it produces, and prompts learning and further research.
 
#    How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
I increased layers of security by implementing monthly dependency checks, RSA to log into the webserver, and SHA-256 to transperse data in and out of our webserver. In the future it will be of interest to do automated testing to find vulnerabilities in the running application, meaning penetration testing, and perhaps contracting white-hats to test our security. 

#    How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
Through thorough testing and code analysis as I developed, and recurrent Owasp checker runs whenever a dependency was added or modified, I was able to check for new vulnerabilities in a meaningful way. 

#    What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
I found the entire class quite helpful in learning about new resources, tools, and best coding practices, so I plan on employing alot of these things in future tasks both at school and working in the field. Learning about the cybersecurity community and resources like Owasp and NIST and the tools such as the dependency checker and certificate generator were quite helpful, as well as Eclipse's plugin manager, and I also found that good documentation, planning, and input validation all play a critical role in the development of competent software. 

#    Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
I would certainly show them my hash encryption implementations. Producing effective real-world encryption techniques is an incredibly competent skillset. 
