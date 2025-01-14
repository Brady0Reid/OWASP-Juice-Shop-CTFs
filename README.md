<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>ITT-340 Pen Testing Report</title>
</head>
<body>
<h1>ITT-340 Pen Testing Report</h1>

<h2>Table of Contents</h2>
<ol>
    <li>ITT-340 Final Report Guidelines</li>
    <li>Solving Improper Input Validation (Zero Stars) Challenge</li>
    <li>Confidential Document Exposure</li>
    <li>DOM XSS</li>
    <li>Error Handling (Security Misconfiguration)</li>
    <li>Missing Encoding</li>
    <li>Outdated Whitelist (Unvalidated Redirects)</li>
    <li>Privacy Policy</li>
    <li>Repetitive Registration</li>
    <li>Login Admin</li>
    <li>Classic Stored XSS</li>
    <li>Appendix</li>
</ol>

<h2>ITT-340 Final Report Guidelines</h2>
<ul>
    <li><strong>Title:</strong> ITT-340 Pen Testing Report</li>
    <li><strong>Author:</strong> Brady Reid</li>
</ul>

<h3>Versioning Control</h3>
<table border="1" cellpadding="5" cellspacing="0">
    <thead>
        <tr>
            <th>Version</th>
            <th>Date</th>
            <th>Author</th>
            <th>Changes</th>
        </tr>
    </thead>
    <tbody>
        <tr><td>1</td><td>12/15/2024</td><td>Brady Reid</td><td>Improper Input Validation (Zero Stars)</td></tr>
        <tr><td>1.2</td><td>12/15/2024</td><td>Brady Reid</td><td>Confidential Document Exposure</td></tr>
        <tr><td>1.3</td><td>12/15/2024</td><td>Brady Reid</td><td>DOM XSS</td></tr>
        <tr><td>1.4</td><td>12/15/2024</td><td>Brady Reid</td><td>Error Handling (Security Misconfiguration)</td></tr>
        <tr><td>1.5</td><td>12/15/2024</td><td>Brady Reid</td><td>Missing Encoding</td></tr>
        <tr><td>2.0</td><td>12/15/2024</td><td>Brady Reid</td><td>Outdated Whitelist (Unvalidated Redirects)</td></tr>
        <tr><td>2.2</td><td>12/15/2024</td><td>Brady Reid</td><td>Privacy Policy</td></tr>
        <tr><td>2.3</td><td>12/15/2024</td><td>Brady Reid</td><td>Repetitive Registration</td></tr>
        <tr><td>2.4</td><td>12/15/2024</td><td>Brady Reid</td><td>Login Admin</td></tr>
        <tr><td>2.5</td><td>12/15/2024</td><td>Brady Reid</td><td>Classic Stored XSS</td></tr>
    </tbody>
</table>

<hr>

<h2>Challenges</h2>

<h3>Solving Improper Input Validation (Zero Stars)</h3>
<p>Objective: Exploit a vulnerability caused by insufficient input validation to submit an invalid rating of zero stars.</p>
<p><strong>Outcome:</strong> The application accepted a zero-star rating, demonstrating a lack of proper input validation.</p>

<h4>Recommendations:</h4>
<ul>
    <li>Implement server-side validation for all inputs.</li>
    <li>Provide immediate client-side feedback using robust validation mechanisms.</li>
    <li>Reject invalid inputs and display clear error messages.</li>
</ul>

<hr>

<h3>Confidential Document Exposure</h3>
<p>Objective: Exploit a vulnerability in OWASP Juice Shop to access sensitive documents.</p>
<p><strong>Outcome:</strong> Confidential documents, such as backup.sql, were accessed due to improper access controls.</p>

<h4>Recommendations:</h4>
<ul>
    <li>Enforce strict access controls.</li>
    <li>Disable directory listing on the server.</li>
    <li>Secure files with appropriate permissions.</li>
</ul>

<hr>

<h3>DOM XSS</h3>
<p>Objective: Exploit a DOM-based XSS vulnerability to execute malicious JavaScript.</p>
<p><strong>Outcome:</strong> Malicious scripts executed due to improper input handling in the browser's DOM.</p>

<h4>Recommendations:</h4>
<ul>
    <li>Sanitize user inputs with libraries like DOMPurify.</li>
    <li>Avoid using <code>innerHTML</code> or <code>eval</code>.</li>
    <li>Implement Content Security Policy (CSP).</li>
</ul>

<hr>

<h3>Error Handling (Security Misconfiguration)</h3>
<p>Objective: Exploit an insecure error-handling mechanism that reveals sensitive information.</p>
<p><strong>Outcome:</strong> Sensitive details, such as stack traces and file paths, were exposed.</p>

<h4>Recommendations:</h4>
<ul>
    <li>Suppress detailed error messages in production environments.</li>
    <li>Use generic error pages.</li>
    <li>Log detailed errors in secure locations.</li>
</ul>

<hr>

<h3>Additional Challenges</h3>
<p>Details for challenges such as Missing Encoding, Outdated Whitelist, Repetitive Registration, Login Admin, and Classic Stored XSS are similarly documented with objectives, steps, outcomes, and recommendations.</p>

<hr>

<h2>Appendix</h2>
<ul>
    <li>Appendix A: Supporting Diagrams</li>
    <li>Appendix B: Detailed Logs</li>
    <li>Appendix C: Code Snippets</li>
</ul>

<hr>

<p><strong>Disclaimer:</strong> This report is fictitious and intended for training purposes only. All testing was conducted in a controlled lab environment.</p>

</body>
</html>
