# CS 305 Portfolio Submission

## Artifact
- Artemis Financial Practices for Secure Software Report (Project Two)

## Reflection

**1. Briefly summarize your client, Artemis Financial, and its software requirements.**  
Artemis Financial is a consulting company that develops customized financial plans for clients, including retirement, savings, investments, and insurance. They needed to modernize their operations and ensure their applications followed secure coding practices to protect sensitive client information. My task was to identify vulnerabilities and implement secure software practices.

**2. What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely?**  
I identified vulnerabilities systematically and provided clear recommendations for fixing them. Coding securely is essential because it protects sensitive data, builds client trust, and ensures business continuity. Secure code reduces the risk of breaches and adds value to the company’s reputation and reliability.

**3. Which part of the vulnerability assessment was challenging or helpful to you?**  
The most challenging part was interpreting dependency-check results and deciding which findings were false positives. This was also helpful because it strengthened my ability to analyze real-world security reports.

**4. How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?**  
I increased security layers by implementing SHA-256 checksum verification, enabling HTTPS/TLS with certificates, and using dependency checks. In the future, I would continue using OWASP tools, static code analysis, and industry frameworks such as NIST and OWASP Top 10 to guide mitigation.

**5. How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?**  
I tested the application to ensure functionality and reran dependency checks after refactoring. This confirmed the app still worked and that no new vulnerabilities were introduced.

**6. What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?**  
I used Maven for dependency management, OWASP Dependency-Check for vulnerability scanning, and secure coding practices such as avoiding hard-coded secrets. These are all valuable for future projects.

**7. Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?**  
I would show my secure coding practices and the vulnerability assessment process to demonstrate my ability to identify risks, implement solutions, and deliver functional, secure applications.
