# CS305-Software-Security


- Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

Artemis Financial is a consulting company that works to create financial plans for its customers. This can be anything from savings plans, retirement plans, insurance and investing plans. They decided that they wanted to implement secure communication
mechanisms to their website. One of their biggest concerns was wanting to make sure that customer info was secure during data transfers. They also wanted to make sure any stord customer data was kept secure.


- What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

During the vulnerability assessment, I successfully identified key areas that required security improvements, particularly regarding secure communication and data verification. Secure coding is integral because it prevents exploits that could compromise sensitive data. Ensuring the integrity, confidentiality, and availability were all top priorities when developing this application. Secure software not only protects a company's reputation and client trust but also ensures compliance, which is crucial for businesses dealing with financial information like Artemis Financial.


- Which part of the vulnerability assessment was challenging or helpful to you?

The most challenging part of the assessment was ensuring that the integration of secure communication mechanisms, such as HTTPS and checksum validation, did not introduce new vulnerabilities. Generating self-signed certificates and ensuring their proper deployment within the application was also a new concept for me. However, this process was helpful in helping me understand cryptographic protocols and how to secure data in transit effectively.


- How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

I added multiple layers of security by implementing cryptographic checksum validation for file verification and transitioning the application from HTTP to HTTPS to secure data. In the future, I would use automated tools like static code analysis tools and dependency-checkers to continuously assess vulnerabilities. These tools along with manual code reviews will help decide on the most effective mitigation techniques.


- How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

After refactoring the code, I ran functional tests to ensure that the application behaved as expected. I also conducted a static code analysis using a dependency-check tool, Maven, to verify that no new vulnerabilities were introduced during the refactoring of the code. Manual code review further ensured the application’s functionality and compliance with security protocols.


- What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

In this project, I used secure coding practices,SpringBoot, RestAPI, static analysis tools (like Maven dependency-check), and Java Keytool for generating self-signed certificates. These tools, along with best practices like proper input validation, encryption, and secure communication protocols (HTTPS), will be invaluable in future projects. Additionally, following the OWASP guidelines helped to ensure adherence to industry-standard security measures.


- Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

From this project, I could showcase my ability to assess and mitigate security vulnerabilities, implement secure communication protocols (HTTPS), integrate cryptographic checksums, and generate self-signed certificates. Screenshots of the checksum verification, secure web communication using HTTPS, and the output of a successful static code analysis would serve as tangible evidence of my secure coding practices and technical proficiency.

