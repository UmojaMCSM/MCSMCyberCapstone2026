# MCSM CyberCapstone 2026

Welcome to your final challenge! This capstone project is your opportunity to showcase the skills, tools, and defensive (or offensive) mindsets you’ve developed throughout this school year. You have the creative freedom to dive deep into a topic that genuinely interests you, format it to match your style, and prove you know your stuff. **NOTE: For this project, you may only work in groups of up to 3 people. IF your group does a presentation, each of you must have a significant role in the presentation.**

---

##  Project Pathways
You must choose **one** of the following three tracks to build your capstone:

* **Option 1: The Expansion Pack** Take one or more labs we completed earlier this school year and significantly extend them. You cannot just submit the same work—you must add new features, deeper analysis, more complex network configurations, or more robust security implementations.
* **Option 2: The Rogue Agent (Choose Your Own Topic)** Have a burning curiosity about a specific cybersecurity domain? Design your own project from scratch. It can cover anything from malware analysis, cryptography, OSINT, and penetration testing, to building a secure home lab. *Note: The topic must be explicitly related to cybersecurity.*
* **Option 3: The Textbook Route** Select any unassigned lab from the text resources and modules currently provided on our Google Classroom. Complete the lab in its entirety and expand on its core conclusions.

---

##  Final Deliverables
To successfully pass this capstone, you must submit two main components:

### 1. Step-by-Step Documentation
Your documentation must be written so that the **average user** (someone without an advanced cybersecurity background) can replicate your exact steps and achieve the same result.
* Must include clear explanations of *why* steps are being taken, not just commands to copy-paste.
* Must include troubleshooting tips for common hurdles.
* Must follow the structured format provided in the template below.

### 2. The Project Demo
You need to show your work in action. You may choose **one** of the following formats for your demo:
* **A Public GitHub Repository:** Complete with organized source code, configuration files, and a well-structured `README.md`.
* **A Project Website:** A live, interactive page detailing your project, architecture diagrams, and findings.
* **A Video Demonstration:** A recorded walkthrough of your running project.  
    * Crucial Note: If you choose video, you must still provide the accompanying source code, scripts, or configuration files used in the video.*

---

##  The Presentation Bonus (+5 Points)
Want to give your final grade a serious boost?  
Sign up to present your capstone to the class during finals week. A successful live or recorded presentation of your project will earn you **5 bonus points added directly to your final average** for the marking period.

---

##  Submission Guidelines
* **Project Blueprint:** Submit which option you chose along with a 3-sentence summary on Google Classroom by **May 27** for approval.
* **Final Deliverables:** Your Documentation and Demo Link/Files are due on **June 19**.

***

# Student Documentation Template
*Students: Copy the markdown section below to create your own `README.md` or submission document.*

```markdown
# [Insert Project Title Here]
### Cybersecurity Capstone Technical Documentation

* **Student Name:** [Your Name]
* **Date:** [Current Date]
* **Course/Period:** [e.g., Cybersecurity Block 3]
* **Selected Pathway:** [Option 1: Expansion Pack / Option 2: Rogue Agent / Option 3: Textbook Route]
* **Project Demo Link:** [Insert GitHub URL, Website Link, or Video Demo URL Here]

---

## 1. Executive Summary & Objective
*Instructions: In 1–2 paragraphs, explain what your project is, what problem it solves, or what security concept it demonstrates. Write this for a non-technical audience. Avoid heavy jargon here, or define it immediately if used.*

* **Project Purpose:** [What does this project do?]
* **Cybersecurity Relevance:** [Why does this matter? How does it relate to real-world defense, offense, or risk mitigation?]

---

## 2. Prerequisites & System Requirements
*Instructions: List absolutely everything an average user needs to have installed, downloaded, or configured before they can start your lab. Do not assume they already have specific tools.*

* **Hardware Requirements:** [e.g., Minimum 8GB RAM, 20GB free hard drive space]
* **Operating System(s):** [e.g., Windows 10/11 hosting a VirtualBox environment running Kali Linux 2026.1]
* **Software/Tools Needed:**
    * [Tool 1 Name](Include link to official download page)
    * [Tool 2 Name](Include link to official download page)
* **Required Baseline Knowledge:** [e.g., Basic familiarity with the Linux Command Line, understanding of basic IP addressing]

---

## 3. Environment Setup & Architecture
*Instructions: Provide a brief description (and ideally a basic visual diagram or text-based layout) of how your environment is set up.*

* **Network/Lab Layout:** [e.g., Kali Linux VM (Attacker) and Metasploitable2 VM (Target) both attached to a Host-Only network adapter]
* **Initial Configurations:** [List any baseline settings the user needs to change before starting, such as turning off Windows Defender or changing network settings in VirtualBox]

---

## 4. Step-by-Step Implementation Guide
*Instructions: This is the core of your documentation. Break your project down into logical phases or steps. For **every single step**, you must provide the action, the exact command/code, what the output should look like, and a plain-English explanation of what is happening.*

### Phase 1: [e.g., Reconnaissance / Initial Setup]

#### Step 1.1: [Name of the Step]
* **Action:** [What should the user click or type?]
* **Command/Code (if applicable):**
    ```bash
    [Insert exact command here, e.g., nmap -sV -O 192.168.56.101]
    ```
* **Expected Output:** [Describe what the user should see on their screen, or insert a placeholder for a screenshot]
* **Plain-English Explanation:** [Explain *why* we ran this command and what the results tell the user in simple terms.]

#### Step 1.2: [Name of the Step]
* **Action:** [What should the user click or type?]
* **Command/Code:**
    ```bash
    
    ```
* **Expected Output:**
* **Plain-English Explanation:**

### Phase 2: [e.g., Exploitation / Defense Implementation]

#### Step 2.1: [Name of the Step]
* **Action:**
* **Command/Code:**
    ```bash
    
    ```
* **Expected Output:**
* **Plain-English Explanation:**

*(Add more steps/phases as necessary to fully cover your project)*

---

## 5. Verification: How to Test Your Setup
*Instructions: How does the reader know they successfully completed your lab? Provide a quick test or checklist to verify success.*

* **Success Criteria 1:** [e.g., You can successfully ping the firewall from the secure zone.]
* **Success Criteria 2:** [e.g., The log file in `/var/log/secure` updates with an alert flag when an unauthorized login attempt occurs.]

---

## 6. Troubleshooting & Common Pitfalls
*Instructions: Think back to the hurdles you faced while building this. List at least 2 or 3 common errors a user might encounter and exactly how to fix them.*

* **Issue 1:** [e.g., "Connection Timeout" error when trying to scan the target VM.]
    * **Fix:** [e.g., Ensure both virtual machines are set to the same "Host-Only" or "NAT Network" adapter in VirtualBox settings, and verify they are on the same subnet.]
* **Issue 2:** [e.g., Command returns "Permission Denied".]
    * **Fix:** [e.g., You must run this command with administrative privileges. Prepend `sudo` to the beginning of the command.]

---

## 7. Conclusion & Security Takeaways
*Instructions: Wrap up your documentation by summarizing what was achieved and discussing the defensive or offensive takeaways.*

* **What was learned:** [Briefly summarize the technical takeaways.]
* **Defensive Mindset:** [How does an administrator defend against the attack demonstrated, or how does this configuration harden a network against real-world threats?]

---

## 8. References & Citations
*Instructions: List any text resources, documentation pages, GitHub repos, or Google Classroom modules you utilized to research or build this project.*

1.  [Resource Name/Author] - [Module Title/URL]
2.  [Resource Name/Author] - [Module Title/URL]
