# 8-1-Jornal-Portfolio

1. Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
**Client Summary: Artemis Financial**

**Client**: Artemis Financial is a consulting firm that specializes in creating personalized financial plans for its customers, including areas like savings, retirement, investments, and insurance.
**Issue**: Artemis Financial wanted to modernize its operations and secure its RESTful web API to protect against external threats. They sought expertise to ensure their software used the latest security practices and was protected from vulnerabilities.

2. What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
**Addressing Software Security Vulnerabilities**
**What Did I Do Well?**
I successfully identified and mitigated several software security vulnerabilities in Artemis Financial's system. This was done by thoroughly assessing the application’s code, analyzing the API endpoints for vulnerabilities, and applying security patches to address those risks.
**Why Is It Important to Code Securely?**
Coding securely ensures that sensitive data is protected from malicious attacks, unauthorized access, and other threats. Secure coding prevents breaches, financial losses, and damage to a company's reputation. It builds trust with clients by ensuring their information is safe and adds long-term value by minimizing the risks of data breaches or legal liabilities.

3. Which part of the vulnerability assessment was challenging or helpful to you?
**Challenges in Vulnerability Assessment**
**Challenges**:
One of the most challenging parts of the vulnerability assessment was prioritizing which vulnerabilities needed immediate attention. This required a deep understanding of the potential impact of each vulnerability.
**Helpful Aspects**:
Learning to use automated tools, such as vulnerability scanners and dependency checks, helped streamline the process and provided valuable insights into the underlying security risks.

4. How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
**Increasing Layers of Security**
**How I Increased Security**:
I employed multiple security layers by implementing authentication and authorization mechanisms, encrypting sensitive data, using secure communication protocols like HTTPS, and hardening API endpoints against injection attacks and other common vulnerabilities.


**Future Vulnerability Assessments**:
In the future, I would use tools like OWASP ZAP, Snyk, or dependency-check plugins to continuously assess vulnerabilities. Deciding on mitigation techniques would involve prioritizing risks based on their severity and potential business impact.

5. How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
**Ensuring Functionality and Security**
**Functional and Secure Code**:
After refactoring the code, I ensured the application remained functional and secure by running both automated and manual tests. This included unit tests, integration tests, and security tests, as well as validating the application against known vulnerabilities using scanning tools.
**Checking for New Vulnerabilities**:
I re-ran the vulnerability assessments after the refactoring process to ensure no new issues were introduced. I also reviewed the code with security best practices in mind to confirm that the refactoring did not open new attack vectors.

6. What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
**Useful Resources and Tools**
**Resources & Tools Used**:
•	**Static code analysis tools**: These tools automatically check for vulnerabilities during development.
•	**OWASP Top 10 Security Guidelines**: This was crucial in identifying common vulnerabilities.
•	**Maven Dependency Check Plugin**: Used to manage vulnerabilities in dependencies.
These resources and practices helped me ensure a secure development process, and I would recommend them for future tasks.

7. Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
**Demonstrating Skills to Future Employers**
**Work Examples:**
Future employers would appreciate the comprehensive vulnerability assessment and mitigation I conducted. Specifically, I could showcase my ability to:
•	Implement secure coding practices.
•	Identify and mitigate software vulnerabilities.
•	Work within an agile framework to improve both functionality and security.
By presenting before-and-after code samples, vulnerability reports, and documentation on the security improvements made, I can demonstrate my technical and problem-solving skills effectively.
