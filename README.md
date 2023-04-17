# CS-305
Software Security

***Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

Artemis Financial was a financial institution that needed a developer to perform a vulnerability assessment report and create a secure software report for a web API. They had very little knowledge of secure coding practices and software security in general and needed an assessment of vulnerabilities and a public web interface that could be upgraded with secure communication practices. 

***What did you do well when finding your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

I believe I articulated the security vulnerabilities in a way that was direct, concise, and easy to understand for someone not well-educated in software security.
Coding securely is essential to prevent cyber-attacks, data breaches, and other security incidents that can result in significant financial losses, reputational damage, and legal liabilities for a company. In today's digital age, businesses rely heavily on software to run their operations, making them vulnerable to a wide range of cyber threats. Software security helps to protect the company's assets, including its data, infrastructure, and intellectual property. By implementing robust security measures, companies can safeguard against potential threats and reduce the risk of a cyber-attack.  Secondly, software security can add significant value to a company's overall well-being by enhancing its reputation and brand image. Customers are increasingly concerned about the security and privacy of their data, and a company that takes cybersecurity seriously can earn their trust and loyalty. 

***What part of the vulnerability assessment was challenging or helpful to you?

Since all our work was locally based “servers” the client/server secure distributed composing was difficult to follow. Many of the self-signed certificates that I generated for the projects needed to be installed in very specific locations with specific information to be accepted by a web browser’s security settings.

***How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

I will continue to run automated dependency checks and manually review static code for glaring deficiencies or unreadable sections. I increased layers of security by following the vulnerability assessment flowchart and ensuring that work in one area did not introduce a new vulnerability in another area.

***How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

I re-ran the vulnerability assessments before and after refactoring the code and ensured that there were no errors within the code. If there were error messages that could be displayed by improper inputs, I made sure to sanitize the inputs and error messages that would be displayed.

***What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

Dependency checks will become a standard practice of mine to search for known vulnerabilities within code. Creating secure error-handling mechanisms is also a new skill that I will have to grow so that my error message doesn’t reveal too much information about the underlying infrastructure.

***Employers sometimes ask for examples of work that you have completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

I would show them the dependency checks and HTTPS secure status, along with the correct usage of the different cryptographic ciphers. Understanding the dependency checks and showing that I can explain them simply and thoroughly would be something I would feel empowered to share.
