## NYU Application Security Course Projects (Gift Card System)

This repository combines projects completed throughout the Application Security course at NYU, focusing on securing a gift card system across various components:

**Projects:**

* **Application Security 1: Binary Analysis and Fuzzing**
    * Analyzes a gift card binary for vulnerabilities.
    * Automates vulnerability discovery using American Fuzzy Lop (AFL) fuzzing.
* **Application Security 2: Web Application Security**
    * Tests a gift card website for OWASP Top 10 vulnerabilities.
    * Identifies vulnerabilities like SQL injection (SQLi), command injection, and Cross-Site Request Forgery (XSRF).
    * Implements code reviews to fix these vulnerabilities and their root causes.
    * Creates automated test cases for these vulnerabilities.
    * Integrates GitHub Workflows to run these tests on every commit.
* **Application Security 3: Container Security**
    * Reviews Docker and Kubernetes implementation of the gift card website.
    * Ensures sensitive information isn't transmitted between containers without proper security measures like Secrets.
    * Addresses vulnerabilities related to sensitive data transmission.
    * Develops test cases for secure communication within containers.
* **Application Security 4: Mobile Application Security**
    * Analyzes the Android application interacting with the gift card API.
    * Identifies and fixes vulnerabilities within the mobile application.

**Repository Structure:**

This repository is organized by project, with subdirectories for each project (e.g., `application-security-1`, `application-security-2`). Each subdirectory contains relevant code, reports, test cases, and documentation specific to that project.

**Learning Objectives:**

This combined repository demonstrates:

* Techniques for binary analysis and fuzzing.
* Identifying and mitigating web application vulnerabilities.
* Secure containerization practices.
* Mobile application security considerations.
* Integrating automated testing for security throughout the development lifecycle.

**Further Exploration:**

Refer to the individual project subdirectories for detailed documentation and findings. Feel free to contribute or raise issues related to further improving the security of the gift card system.
