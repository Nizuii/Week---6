# ❔ What is CIA Triad.
The CIA Triad stands for:
<ol>
  <li> Confidentiality</li>
  <li>Integrity</li>
  <li>Availability</li>
</ol>
These three principles guide every cyber security decision and are used to design, review, and strengthen security systems.

<h2>1. Confidentiality</h2>
Confidentiality is all about keeping information secret from people who are not allowed to access it. Only authorized users should access the protected data - like passwords, medical records or business documents.
<ul>
  <li><strong>Example:</strong> using a password to login to your email. Without the password others can't see your messages.</li>
  <li>Techniques includes encryption, access control and authentication.</li>
</ul>

<h2>2. Integrity</h2>
Integrity is about ensuring information is accurate and trustworthy. Data must not be changed, corrupted, or deleted by unauthorized people.
<ul>
  <li><strong>Example:</strong> If a file is sent over the internet, you want to ensure it arrives unaltered. Techniques include checksums, hash functions, and digital signatures.</li>
  <li>Integrity helps prevent tampering or errors that could mislead users.</li>
</ul>

<h2>3. Avaiability</h2>
Availability means data and systems are accessible when needed by authorized people. If systems go down (from power loss, attacks, or other issues), availability is lost.
<ul>
  <li><strong>Example:</strong> If you can’t access your online class materials because the website is down, that’s an availability problem.</li>
  <li>Techniques involve backups, redundancy, and network protections like firewalls and anti-DDoS systems.</li>
</ul>

The CIA Triad is not about following rules blindly: it’s about balancing all three, since strict confidentiality can interfere with availability, and vice versa. Every cyber security system, tool, and policy tries to get this balance right.​

# ⚔️ Types of Attacks Affecting the CIA Triad
<h2>Attacks on Confidentiality</h2>
<strong>Goal:</strong> Gain access to private information without permission.
<ul>
  <li>Examples:</li>
  <ul>
    <li><strong>Data Breaches:</strong> Hackers steal personal info from databases (e.g., leaking user emails or bank details).</li>
    <li><strong>Phishing:</strong> Tricking users into giving away passwords via fake emails.</li>
    <li><strong>MITM (Man in the middle):</strong> Intercepting and reading data sent between two parties.​</li>
    <li><strong>Packet Sniffing:</strong> Listening to network traffic to capture credit card numbers or passwords.</li>
  </ul>
  <li>Prevention:</li>
  <ul>
    <li>Use encryption for data at rest and in transit.</li>
    <li>Implement access control policies (like permissions).</li>
    <li>Use strong, unique passwords and multi-factor authentication (MFA).</li>
    <li>Educate users to spot phishing.</li>
  </ul>
</ul>

<h2>Attacks on Integrity</h2>
<ul>
  <li>Example:</li>
  <ul>
    <li><strong>Website defacement:</strong> Hackers change what a site displays to spread false messages.</li>
    <li><strong>SQL Injection:</strong> Exploiting weak code to alter or delete data in databases.</li>
    <li><strong>Ransomware:</strong> Encrypts files and may also tamper with data.</li>
    <li><strong>Malware:</strong> Inserts harmful code that changes files or system settings.</li>
    <li><strong>Insider attacks:</strong> Authorized users exceeding their privileges to change records.</li>
  </ul>
  <li>Prevention:</li>
  <ul>
    <li>Validate and sanitize inputs (to block SQL injection).</li>
    <li>Use file integrity monitoring tools.</li>
    <li>Limit user privileges: "least privilege principle".</li>
    <li>Regularly backup data and check for unauthorized changes.</li>
  </ul>
</ul>

<h2>Attack on Availability</h2>
<ul>
  <li>Example:</li>
  <ul>
    <li><strong>Distributed Denial of Service (DDoS):</strong> Overloads servers so nobody can use them.</li>
    <li><strong>Ransomware:</strong> Locks you out of your data until you pay.</li>
    <li><strong>Hardware failure or natural disasters:</strong> Unexpected outages.</li>
    <li><strong>Network misconfiguration:</strong> Prevents legitimate access.</li>
  </ul>
  <li>Prevention:</li>
  <ul>
    <li>Employ redundant systems (multiple servers or backup hardware).</li>
    <li>Keep regular backups stored safely.</li>
    <li>Use firewalls and anti-DDoS technologies.</li>
    <li>Test disaster recovery plans often.</li>
  </ul>
</ul>

# 🤔 How to achieve CIA Triad.

To achieve the CIA Triad in cybersecurity, organizations and individuals must implement a combination of technical controls, policies, and best practices that protect data confidentiality, ensure its integrity, and guarantee its availability. Here’s how each pillar can be achieved:

<h2>Confidentiality</h2>
<ul>
  <li><strong>Encryption:</strong> Use strong encryption for data at rest (stored) and in transit (being sent over networks).</li>
  <li><strong>Access Controls:</strong> Implement role-based access control (RBAC) and the principle of least privilege, so only authorized users can access sensitive data.</li>
  <li><strong>Authentication:</strong> Require multi-factor authentication (MFA) and strong passwords to verify user identity.​</li>
  <li><strong>Data Classification:</strong> Categorize data by sensitivity and apply appropriate security measures for each level.​</li>
</ul>

<h2>Integrity</h2>
<ul>
  <li><strong>Hashing and Digital Signatures:</strong> Use cryptographic techniques to verify that data has not been altered.​</li>
  <li><strong>File Integrity Monitoring (FIM):</strong> Regularly check for unauthorized changes to files and systems.​</li>
  <li><strong>Change Management:</strong> Implement strict procedures for modifying data or systems, and keep audit logs.</li>
  <li><strong>Version Control:</strong> Track changes and maintain backups to restore data if needed.</li>
</ul>

<h2>Availability</h2>
<ul>
  <li><strong>Redundancy:</strong> Use backup systems, cloud storage, and load balancers to ensure systems remain accessible.</li>
  <li><strong>Disaster Recovery Planning:</strong> Develop and test plans for recovering from outages, attacks, or natural disasters.​</li>
  <li><strong>Regular Maintenance:</strong> Keep systems updated and patched to prevent downtime from vulnerabilities.​</li>
  <li><strong>Incident Response:</strong> Prepare for and quickly respond to incidents that could disrupt service.</li>
</ul>
