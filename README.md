# CS305
Software Security course at SNHU

Artemis Financial is a financial company that develops financial plans for their customers.  This information is extremely high risk as security leaks could expose their client’s information to individuals who can access improperly secured communications and have malicious intent.


I was able to find and analyze dependency vulnerabilities particularly well in this project with the use of OWASP dependency-check.  It is important to code securely because data leaks and other security threats are extremely expensive to both the company's budget and the company's reputation.  Software security adds to the company's reputation and peace of mind.


Working through the vulnerability assessment I found that the OWASP dependency-check was extremely helpful.


I approached the need to increase layers of security by first determining what kind of data was being dealt with and how that data was being transferred.  In the future I would utilize the vulnerability assessment process flow diagram to assess vulnerabilities and utilze training and research to determine mitigation techniques.


I ensured the code and software were secure by creating a self-signed certificate and having the software be HTTPS compliant.  I did a OWASP dependency-check before refatoring the code and suppressed all vulnerabilities.  I then did another check after refactoring to make sure no new vulnerabilities were exposed.  I also did a functional check of the refactored code using the vulnerability assessment process.


I used the following tools and techniques that I will probably use again in the future: self-signed certificate, the OWASP dependency-check, the sha-256 algorithm, HTTPS protocol, and the vulnerabilitiy assessment process.


I would showcase my ability to assess vulnerabilitites and make a plan to mitigate them.
