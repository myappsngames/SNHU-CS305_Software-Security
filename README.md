# SNHU CS305: Software Security
SNHU CS305 Project Two

## Reflection

#### Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
* Overview: Artemis Financial is a consulting company specializing in developing personalized financial plans for its clients. These plans cover various aspects such as savings, retirement, investments, and insurance.
* Problem: The company aims to modernize its operations and enhance its software security. Specifically, they want to implement a file verification mechanism to ensure secure data transmission through their web application. This mechanism will involve using checksums to verify data integrity during transfers.
* Goal: Artemis Financial seeks Global Rain's expertise to integrate secure communication protocols into their existing web application. This will help protect client data and financial information, meeting their software security requirements.

#### What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
* To enhance the security of Artemis Financial’s application, I carefully evaluated its existing code and implemented several measures. I selected a robust encryption algorithm cipher, generated self-signed certificates, and integrated cryptographic hash functions to verify data integrity. I also refactored the code to use HTTPS for secure communication and conducted thorough static and functional testing to identify and address potential vulnerabilities. These comprehensive steps significantly strengthened the application’s security posture, protecting sensitive client data and mitigating the risk of unauthorized access.
* By safeguarding sensitive information from unauthorized access, theft, or corruption, it prevents significant financial losses that can arise from data breaches. Additionally, secure coding ensures compliance with industry regulations, mitigating the risk of fines and penalties. Moreover, it fosters trust between a company and its customers, strengthening relationships and enhancing brand reputation.
* By mitigating the risk of security breaches, it safeguards valuable assets and preserves a company’s reputation. Strong security practices can also provide a competitive advantage, setting a company apart in the market. Adherence to security regulations is essential to avoid legal complications and maintain a positive public image. Having a robust security posture also ensures business continuity, enabling operations to continue even in the face of security incidents.

#### Which part of the vulnerability assessment was challenging or helpful to you?
* Learning which algorithm cipher to implement was helpful. Providing a sound justification for the chosen encryption algorithm was both challenging and rewarding.

#### How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
* I employed a robust encryption algorithm to safeguard data during transmission, and I established a secure connection using self-signed certificates. Additionally, I transitioned from HTTP to HTTPS to enable encrypted communication. Finally, I incorporated a checksum verification step to ensure data integrity throughout the transmission process. These comprehensive measures significantly enhanced the application’s security posture, protecting sensitive information from unauthorized access and tampering.

#### How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
* To ensure the code and software application remained functional and secure after refactoring, I conducted rigorous testing and verification. I meticulously reviewed the modified code for syntactical and logical errors, ensuring that the changes did not introduce unintended consequences. Additionally, I performed comprehensive functional testing to verify that the application continued to operate as expected and that the new security measures were effective. To assess whether the refactoring process had inadvertently introduced new vulnerabilities, I employed static analysis tools to scan the code for potential weaknesses. By following these thorough testing procedures, I was able to maintain the application's functionality and enhance its overall security.

#### What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
* Encryption Libraries: Libraries like OpenSSL or Bouncy Castle provide pre-built cryptographic algorithms and functions, making it easier to implement encryption and decryption.
* Certificate Management Tools: Tools like Java Keytool can be used to generate, manage, and export certificates.
* Static Analysis Tools: Tools like SonarQube or FindBugs can help identify potential security vulnerabilities in code.
* Security Best Practices Guides: Following security best practices guidelines, such as those provided by OWASP, can help prevent common vulnerabilities.
* Secure Coding Practices: Adopting secure coding practices, like input validation, output encoding, and avoiding hardcoded credentials, can significantly reduce the risk of vulnerabilities.

#### Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
* Technical Skills and Knowledge
  * Encryption: Demonstrate my understanding of encryption algorithms, key management, and certificate-based authentication by providing examples of how I implemented these techniques.
  * Secure Coding Practices: Showcase my knowledge of secure coding practices by highlighting specific examples of how I avoided common vulnerabilities like SQL injection, cross-site scripting, or buffer overflows.
  * Static Analysis Tools: Discuss my experience with using static analysis tools to identify potential vulnerabilities in the code.

* Problem-Solving and Analytical Skills
  * Vulnerability Assessment: Explain how I conducted a thorough vulnerability assessment, identifying potential weaknesses and recommending appropriate mitigation strategies.
  * Risk Assessment: Describe how I evaluated the risks associated with different vulnerabilities and prioritized remediation efforts.
  * Problem-Solving: Highlight specific instances where I faced challenges during the assessment and how I overcame them.


