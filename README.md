# Artemis-Financial-Practices-for-Secure-Software-Report
This report reviews Artemis Financial’s web application for security risks, identifies vulnerabilities through code review and dependency scanning, and recommends improvements such as stronger encryption, input validation, secure error handling, and updated libraries.

Module Eight Journal

Summary of the Client and Software Requirements:
Artemis Financial is a company that builds customized financial plans for clients, including savings, retirement, investments, and insurance. Because they handle sensitive financial data, they needed their web application reviewed for security issues. My job was to identify vulnerabilities in their RESTful API and recommend ways to make the application more secure.

What I Did Well:
I did well identifying vulnerabilities through both manual code review and dependency‑check results. I was able to spot outdated libraries, missing validation, and insecure error handling. Secure coding is important because it protects sensitive data, prevents attacks, and helps maintain trust with users especially in a financial setting.

Challenges and Helpful Parts:
The most challenging part was connecting the manual findings with the dependency‑check results, especially when dealing with transitive dependencies. Even though it was challenging, it helped me understand how different parts of the system interact and how vulnerabilities can spread through third‑party libraries.

Increasing Layers of Security:
I increased security by enforcing HTTPS, improving input validation, updating vulnerable libraries, and tightening error handling. In the future, I would continue using tools like OWASP Dependency‑Check, static analysis tools, and secure coding guidelines to evaluate vulnerabilities and choose the right mitigation techniques.

Ensuring Functionality and Security:
After refactoring, I tested the application endpoints, checked the certificate setup, and reran dependency scans to make sure no new vulnerabilities were introduced. I also followed secure coding practices like sanitizing inputs, removing hard‑coded values, and improving encapsulation to keep the application both functional and secure.

Resources, Tools, and Practices Used:
I used OWASP Dependency‑Check, Maven, secure coding patterns, HTTPS configuration, and Spring Security best practices. These tools and techniques will be useful in future projects, especially when working with applications that handle sensitive information.

What I Can Show Future Employers:
This project shows that I can perform a full vulnerability assessment, understand static testing results, and apply secure coding practices to a real application. It demonstrates my ability to analyze code, identify risks, and implement improvement skills that are valuable in software development and cybersecurity roles.
