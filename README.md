# PAM-Pluggable-Authentication-Module-
This project secures an Ubuntu web server by enabling PAM authentication. It requires users to enter valid system credentials to access protected content. The project sets up the server, configures PAM, and tests access before and after to show improved security.

1. Project Overview:
This project focuses on securing an Ubuntu web server by enabling PAM (Pluggable Authentication Modules) to require system-level usernames and passwords before accessing protected web content. The main objective is to demonstrate how PAM can be used to enforce strong access control on a web server and reduce unauthorized access risks.

2. Project Relevance:
Securing access to web servers is essential in cybersecurity and digital forensics as weak authentication mechanisms are a common attack vector. PAM is a foundational Linux security tool used in real-world system administration so understanding how it works is valuable for managing user authentication, protecting sensitive data, and supporting incident response. I chose this project because it provides hands-on expereience with web security, Linux system configuration, and authentication mechanisms.

3. Methodology
Setup & Environment
- Operating System: Ubuntu
- Web Server: Apache2 or Nginx
- Authentication: PAM with system accounts
- Tools: Terminal, nano/vim, Apache/Nginx modules, system logs, browser for testing

Workflow:
[Workflow.pdf](https://github.com/user-attachments/files/23783888/Workflow.pdf)

Step-by-Step Process:
1. Install Ubuntu in VMWare Workstation Pro
2. Set up a basic Apache or Nginx web server
3. Create test user accounts in Ubuntu
4. Try accessing the site before PAM is enabled
5. Enable PAM authentication on the web server
   - For Apache: configure .htaccess or use libapache2-mod-authz-pam
6. Restart the web server and test authentication
7. Test to see if it requires the user to enter a username/password
8. Review system logs to verify authentication attempts

4. Results:

5. Conclusion:
Enabling PAM on an Ubuntu web server helps improves security by enforcing system-level authentication. This project shows how simple configuration changes can protect sensitive content and prevent unauthorized access.

Lessons Learned:
- How PAM integrates with web services
- Importance of access control in cybersecurity
- How to analyze authentication logs for security monitoring

Next Steps:
- Add 2MFA
- Use LDAP or Active Directory for centralized authentication




