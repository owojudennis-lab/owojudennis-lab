<h1>Hi, I'm Dennis 👋</h1>
<h3>SOC Analyst | Cloud Security | Final-Year Computer Engineering Student</h3>

<p>
I'm a final-year Computer Engineering student (graduating 2026) building hands-on experience
across cybersecurity monitoring and AWS cloud infrastructure. My near-term goal is a SOC Analyst
role, with cloud security as the direction I'm building toward long-term.
</p>

<h2>🛡️ Cybersecurity & SOC Projects</h2>

- <b>Wazuh SIEM & Brute-Force Detection Lab</b>
  - Deployed Wazuh manager on Ubuntu Server, enrolled Windows 10 and AD endpoints
  - Wrote a custom Wazuh detection rule for RDP brute-force attempts, simulated via Kali/xfreerdp
  - Hardened the Windows endpoint against the same attack (account lockout policy, CIS benchmarks) and validated detection end-to-end
  - [View repo →](https://github.com/owojudennis-lab/Wazuh-Brute-Force-Detection-Windows-Endpoint-Hardening-Lab)

- <b>Sysmon Integration & Endpoint Visibility</b>
  - Installed and configured Sysmon on Windows 10 for process-level telemetry
  - Integrated Sysmon logs into Wazuh and compared Event Viewer output against Wazuh alerts to find detection gaps
  - Investigated missing fields (`win.eventdata.image`, `targetObject`) and explored rule tuning to close them

- <b>Active Directory Monitoring Lab</b>
  - Built a Windows AD domain controller in a virtual lab and connected it to Wazuh for authentication monitoring
  - [View repo →](https://github.com/owojudennis-lab/active-directory-wazuh-monitoring)

<h2>☁️ AWS Cloud Projects</h2>

- <b>EC2 Monitoring with CloudWatch & SNS</b>
  - EC2 instance monitored via CloudWatch Agent, IAM role scoped to least privilege, CloudWatch Alarm → SNS email alerting on high CPU
  - [View repo →](https://github.com/owojudennis-lab/aws-ec2-cloudwatch-monitoring)

- <b>Static Website on S3 + CloudFront</b>
  - S3-hosted static site distributed globally via CloudFront, secured with Origin Access Control (no public bucket)
  - [View repo →](https://github.com/owojudennis-lab/aws-s3-cloudfront-static-website)

<h2>🧰 Tools & Technologies</h2>
<p>
Wazuh · Sysmon · MITRE ATT&CK · Wireshark · Splunk (learning) · AWS (EC2, IAM, CloudWatch, SNS, S3, CloudFront) ·
Ubuntu Server · Windows Server/AD · Oracle VirtualBox · Linux
</p>

<h2>📈 Currently</h2>
<ul>
  <li>Preparing for AWS Certified Cloud Practitioner</li>
  <li>Building detection engineering and log analysis depth for SOC work</li>
  <li>Applying to SOC Analyst / Junior Security Analyst roles</li>
</ul>

<h2>🤳 Connect with me</h2>
<p>
<a href="https://github.com/owojudennis-lab"><img src="https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github&logoColor=white" /></a>
<a href="https://www.linkedin.com/in/owoju-dennis/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
</p>
