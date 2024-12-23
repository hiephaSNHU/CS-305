1.	Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
Artemis Financial required a secure software solution to protect sensitive data transmitted over their systems. The company needed to ensure the integrity of its data and secure communication channels while addressing vulnerabilities in their software dependencies.
2.	What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
I effectively used tools like OWASP Dependency-Check to identify vulnerabilities in the software's dependencies and updated libraries to address those issues. Secure coding prevents data breaches and unauthorized access, thereby maintaining client trust and protecting the company's reputation and financial assets.
3.	Which part of the vulnerability assessment was challenging or helpful to you?
Updating vulnerable dependencies and ensuring compatibility with the rest of the application was challenging but instrumental in reducing the overall security risk.
4.	How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
Layers of security were increased by implementing SHA-256 hashing for data integrity and enabling HTTPS for secure communications using a self-signed certificate. In the future, I would continue to use OWASP tools, static code analysis, and third-party vulnerability databases to assess and mitigate risks.
5.	How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
The application's functionality was verified through manual testing of the /hash endpoint, ensuring it returned expected results. After refactoring, I re-ran the Dependency-Check tool and conducted manual reviews to ensure no new vulnerabilities were introduced.
6.	What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
Tools like OWASP Dependency-Check, secure coding practices like SHA-256 hashing, and HTTPS configuration best practices are valuable for future projects.
7.	Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
I would showcase my ability to identify and mitigate software vulnerabilities, implement secure communications, and adhere to industry best practices for secure software development, as demonstrated in this project.
