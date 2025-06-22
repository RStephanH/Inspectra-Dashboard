# Inspectra Dashboard
Inspectra Dashboard: Frontend for Web Vulnerability Scanning

Inspectra Dashboard serves as the frontend interface for the Inspectra project, which combines the powerful Inspectra Engine built on Express.js. This comprehensive tool is designed to help developers and security professionals identify and address common vulnerabilities in web applications.

Key Features:
- User-Friendly Interface: The Inspectra Dashboard provides an intuitive and accessible interface, allowing users to easily navigate through various scanning options and results.
- Integration with Inspectra Engine: The dashboard seamlessly integrates with the Inspectra Engine, leveraging its capabilities to perform in-depth scans for vulnerabilities.
- Vulnerability Detection: The dashboard focuses on identifying critical security issues, including:
    - Content Security Policy (CSP) Issues: Evaluates CSP configurations to prevent unauthorized content loading.
    - HTML Injection Flaws: Detects potential vulnerabilities that could allow malicious HTML injection.
    - JavaScript Vulnerabilities: Analyzes JavaScript code for common security weaknesses.
    - Cross-Site Scripting (XSS) Attacks: Checks for XSS vulnerabilities that could compromise user data.
- Reporting and Mitigation Guidance: After scanning, the dashboard provides detailed reports on identified vulnerabilities along with recommendations for remediation, helping users to effectively mitigate risks.
With Inspectra Dashboard, users can proactively enhance the security of their web applications by leveraging the robust scanning capabilities of the Inspectra Engine. This combination empowers developers to maintain secure and resilient web environments.


To get started, take a look at src/app/page.tsx.

## Running the App Locally

To run the application on your local machine, you'll need to start both the Next.js development server and the Genkit development server.

1.  **Start the Next.js development server:**
    Open a terminal and run:
    ```bash
    npm run dev
    ```
    This will typically start the web application on `http://localhost:9002`.


Make sure you have Node.js and npm installed. Any necessary packages will be installed automatically if they are added to `package.json`.
