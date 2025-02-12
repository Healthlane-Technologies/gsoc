# Project Ideas

### 1. Improved Application Deployment Process

#### Summary:
This project aims to enhance the deployment process of new applications by ensuring that the Zango server can accommodate updates without necessitating a restart. This approach will minimize downtime and improve the overall user experience by allowing continuous service availability during deployment.

#### Expected outcomes:

#### Skills:
- Docker
- Zango
- Django
- Python

#### Potential Mentors:
- [Harsh Shah](https://github.com/shahharsh176)
- [Deepak Dinesh](https://github.com/deepakdinesh1123)

#### Size: 350 hours

#### Difficulty rating: Hard



### 2. Support ManyToMany Field in Zango

#### Summary:
This project aims to extend the functionality of Zango to support ManyToMany fields, enabling users to create relationships between models in a flexible and efficient manner.

#### Expected outcomes:

#### Skills:
- Django
- Python
- Zango
- PostgreSQL

#### Potential Mentors:
- [Harsh Shah](https://github.com/shahharsh176)
- [Deepak Dinesh](https://github.com/deepakdinesh1123)
- [Bhuvnesh Sharma](https://github.com/devilsautumn)

#### Size: 350 hours

#### Difficulty rating: Hard



### 3.Support for caching in Zango

#### Summary:
This project aims to extend the functionality of Zango to support caching, allowing users to store and retrieve data from the database in a more efficient manner.

#### Expected outcomes:

#### Skills:
- Django
- Python
- Zango
- Redis

#### Potential Mentors:
- [Harsh Shah](https://github.com/shahharsh176)
- [Deepak Dinesh](https://github.com/deepakdinesh1123)
- [Bhuvnesh Sharma](https://github.com/devilsautumn)

#### Size: 350 hours

#### Difficulty rating: Hard



### 4. Security Settings Page in App Panel

#### Summary:
This project aims to add a security settings page to the Zango app panel, allowing users to configure security settings from app panel itself.
Complete details of the project can be found in this github issue: https://github.com/Healthlane-Technologies/Zango/issues/411

#### Expected outcomes:
The Security Settings page should display the following items, with a visual indicator (e.g., green for secure, red for insecure) for each:

- Debug Mode: Verify if Debug = False.
- IP Restriction: Ensure App Panel access is IP-restricted. Show the allowed IP's
- Account Lockout Time: Display the duration of account lockouts after failed attempts.
- Allowed Password Attempts: Show the configured limit for failed login attempts.
- Password Age: Display the maximum age for passwords before expiration.
- HTTPS Only: Verify if HTTPS-only is enforced.
- Password Age Policies: Check if password age policies are in place for all users.
- Password Strength Policies: Confirm if password strength requirements (e.g., complexity, length) are enforced for all users.
- Default IDs or Passwords: Ensure no default IDs or passwords are active in production.
- Concurrent Sessions Disabled: Verify if concurrent sessions are disallowed to prevent session hijacking.
- Server Time Synchronization: Confirm if the server time is synchronized with NTP.
- Two-Factor Authentication (2FA): Check if 2FA is enforced for all user accounts in applications.
- SSO/OIDC: Verify if users SSO/OIDC is enforced for all application users.
- Cross-Site Scripting (XSS) Protection: Verify if XSS protection headers are enabled in the HTTP response (e.g., - X-XSS-Protection).
- Content Security Policy (CSP): Ensure a Content Security Policy is set to help prevent data injection attacks like XSS.
- SQL Injection Protection: Confirm that prepared statements or ORM protections are in place to prevent SQL injection - vulnerabilities.
- Clickjacking Protection: Check for X-Frame-Options headers to prevent clickjacking attacks.
- Secure Cookies: Verify that cookies have secure and HttpOnly flags set to prevent access by JavaScript and ensure they’re sent only over HTTPS.
- API Rate Limiting: Ensure API endpoints have rate-limiting mechanisms to mitigate brute-force and DoS attacks.
- Audit Logging: Confirm if audit logging is enabled for critical actions (e.g., login attempts, password changes, sensitive data access).
- Data Encryption in Transit: Verify that data in transit is encrypted, typically with TLS, for secure communication.
- Security Headers Compliance: Check for other essential HTTP security headers (e.g., Strict-Transport-Security, X-Content-Type-Options, Referrer-Policy).
- External Resources Control: Confirm that only trusted and necessary external resources (e.g., JavaScript libraries, stylesheets) are allowed.

#### Skills:
- Django
- Python
- Zango
- PostgreSQL

#### Potential Mentors:
- [Vishal Revadi](https://github.com/vishal-revadi)
- [Ravi Patel](https://github.com/sukuna28)
- [Bhuvnesh Sharma](https://github.com/devilsautumn)

#### Size: 90 hours

#### Difficulty rating: Medium