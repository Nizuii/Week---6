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
  <li>Prevention</li>
  <ul>
    <li>Use encryption for data at rest and in transit.</li>
    <li>Implement access control policies (like permissions).</li>
    <li>Use strong, unique passwords and multi-factor authentication (MFA).</li>
    <li>Educate users to spot phishing.</li>
  </ul>
</ul>
