<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cybersecurity Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 40px;
            background-color: #f4f4f4;
        }
        .container {
            max-width: 900px;
            margin: auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        h1, h2 {
            color: #0077B5;
        }
        .experience {
            margin-bottom: 20px;
            padding: 10px;
            background: #eef3f7;
            border-left: 5px solid #0077B5;
        }
        .screenshot {
            width: 100%;
            max-width: 600px;
            border-radius: 5px;
            margin-top: 10px;
        }
        .linkedin-btn {
            display: inline-block;
            background-color: #0077B5;
            color: white;
            padding: 10px 15px;
            text-decoration: none;
            font-weight: bold;
            border-radius: 5px;
            margin-top: 20px;
            display: block;
            text-align: center;
            max-width: 200px;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Cybersecurity Portfolio</h1>
        <p>Welcome to my professional cybersecurity portfolio. Here, I showcase my experience, skills, and completed projects.</p>


        <!-- About Me Section -->
        <h2>About Me</h2>
        <p style="text-align: justify; line-height: 1.6;">
            I am a passionate Information Technology professional with a growing specialization in Cybersecurity.
            My journey began as a certified Oracle Expert and Oracle Certified Associate, where I gained experience in Linux applications and database management using SQL.
            To further solidify my technical expertise, I pursued a Master’s degree in Information Technology with a focus on Business Intelligence.
            During my studies, I explored Cybersecurity, which became an integral part of my coursework and projects.
            I applied cybersecurity principles to fortify web applications and enhance their security.
            Some of these projects are included in this portfolio and are currently running.
        </p>

        <!-- About Me Section -->
         <h2>Certification</h2>
         <p>CompTIA Security+ (SY0-601), (expected 5/25) </p>
         <p>Google Cybersecurity Professional Certificate</p>
         <p>Oracle Database Administrator Ceritfied Associate</p>
         <p>Oracle Database SQL Ceritfied Expert</p>

          <!-- Skill Section -->
          <h2>Skills</h2>
         <p>linux Administrator</p>
         <p>NIST Framework</p>
         <p>SQL </p>
         <p>Python</p>
         <p>Log analysis using Wireshark, SIEM, and Splunk</p>

        <!-- Experience Section -->
        <h2>Experience</h2>

        <div class="experience">
            <h3>Network Security & Vulnerability Assessment</h3>
            <p>Conducted penetration testing and network vulnerability scanning using Nmap, Wireshark, and Metasploit**.</p>
            <img src="images/Nmap.png" alt="Network Scan" class="screenshot">
            <img src="images/nmap2.png" alt="Network Scan" class="screenshot">
        </div>

        <div class="experience">
            <h3>SQL</h3>
            <p>Successfully completed multiple CTF challenges on **TryHackMe**, SQL on Google Cybersecurity, focusing on **web exploitation, cryptography, and privilege escalation**.</p>
            <img src="images/access_control.png" alt="Access Control and Management" class="screenshot">
            <img src="images/Least_privilege audit.png" alt="Access Control and Insider Threats" class="screenshot">
        </div>

        <div class="experience">
            <h3>Security Information and Event Management (SIEM)</h3>
            <p>Worked with SIEM tool to analyze and respond to security incidents.</p>
            <img src="images/siem.png" alt="SIEM Logs" class="screenshot">
            <img src="images/alertlog2.png" alt="SIEM Logs" class="screenshot">
            <img src="images/siem2.png" alt="SIEM Logs" class="screenshot">
            <img src="images/ipaddresslock.png" alt="SIEM Logs" class="screenshot">
            <img src="images/ipblocksite.png" alt="SIEM Logs" class="screenshot">
        </div>

        <!-- LinkedIn Profile -->
        <a href="https://www.linkedin.com/in/adewalealadeloye/" target="_blank" class="linkedin-btn">View My LinkedIn</a>

    </div>

</body>
</html>
