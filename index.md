layout: single
author_profile: true
---
# Sharon Mwanje Lusega - Professional Portfolio

Welcome to my professional portfolio website, showcasing my expertise in IT support, networking, cloud security, and cybersecurity. This site, built with HTML, CSS, and Tailwind CSS, serves as my digital identity for potential employers, academic peers, and collaborators. It includes my resume, projects, lab challenges, and contact information.

## Website Preview
[Live Demo](#) *(Replace with actual GitHub Pages link after deployment)*

## Table of Contents
- [Home](#home)
- [Resume](#resume)
- [Projects](#projects)
- [Lab Challenges](#labchallenges)
- [Contact](#contact)

## index.html
Below is the complete HTML code for the portfolio website. To host this on GitHub Pages, copy the content into an `index.html` file in your GitHub repository and enable GitHub Pages.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sharon Mwanje Lusega - Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        .smooth-scroll {
            scroll-behavior: smooth;
        }
    </style>
</head>
<body class="bg-gray-100 text-gray-800 smooth-scroll">
    <!-- Navigation -->
    <nav class="bg-white shadow fixed w-full z-10">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-16">
                <div class="flex items-center">
                    <span class="font-bold text-xl">Sharon Mwanje Lusega</span>
                </div>
                <div class="flex items-center space-x-4">
                    <a href="#home" class="text-gray-600 hover:text-blue-600">Home</a>
                    <a href="#resume" class="text-gray-600 hover:text-blue-600">Resume</a>
                    <a href="#projects" class="text-gray-600 hover:text-blue-600">Projects</a>
                    <a href="#challenges" class="text-gray-600 hover:text-blue-600">Lab Challenges</a>
                    <a href="#contact" class="text-gray-600 hover:text-blue-600">Contact</a>
                </div>
            </div>
        </div>
    </nav>

    <!-- Home Section -->
    <section id="home" class="min-h-screen flex items-center justify-center bg-gradient-to-r from-blue-500 to-indigo-600 text-white">
        <div class="text-center max-w-2xl mx-auto px-4">
            <img src="https://via.placeholder.com/150" alt="Sharon Mwanje Lusega" class="rounded-full w-32 h-32 mx-auto mb-4">
            <h1 class="text-4xl font-bold mb-2">Sharon Mwanje Lusega</h1>
            <p class="text-xl">IT Support, Networking, Cloud Security & Cybersecurity Specialist</p>
        </div>
    </section>

    <!-- Resume Section -->
    <section id="resume" class="py-16 max-w-4xl mx-auto px-4">
        <h2 class="text-3xl font-bold mb-8 text-center">Resume</h2>
        <div class="space-y-8">
            <div>
                <h3 class="text-2xl font-semibold">Professional Summary</h3>
                <p class="mt-2">Proactive IT Support, Networking, Cloud Security, and Cybersecurity Specialist with over 3 years of experience providing technical assistance in fast-paced environments. Adept at deploying secure infrastructures, enforcing data protection policies, and ensuring business continuity through robust IT strategies.</p>
            </div>
            <div>
                <h3 class="text-2xl font-semibold">Education</h3>
                <p class="mt-2"><strong>Bachelor in Business Information Technology</strong> - Strathmore University, Sept 2018 - June 2021 (Second Class Honors)</p>
                <p><strong>Diploma in Business Information Technology</strong> - Strathmore University, May 2014 - March 2016</p>
                <p><strong>Kenya Certificate of Secondary Education (K.C.S.E)</strong> - Moi Girls High School, Vokoli, March 2009 - Dec 2012</p>
            </div>
            <div>
                <h3 class="text-2xl font-semibold">Work Experience</h3>
                <p class="mt-2"><strong>ICT Support Officer (Contract)</strong> - Kenya Revenue Authority, Jan 2023 - Dec 2024</p>
                <ul class="list-disc ml-6">
                    <li>Maintained ICT equipment inventory and ensured compliance with IT policies.</li>
                    <li>Supported hardware, software, and network components, including routers and firewalls.</li>
                    <li>Implemented cybersecurity controls and disaster recovery strategies.</li>
                </ul>
                <p class="mt-2"><strong>Volunteer Teacher</strong> - Kibera Pride Initiative Organization, March - October 2022 (225 hours)</p>
                <ul class="list-disc ml-6">
                    <li>Provided educational support and community service.</li>
                </ul>
                <p class="mt-2"><strong>IT Support Technician</strong> - Touchdown Systems Limited, Oct 2020 - Dec 2021</p>
                <ul class="list-disc ml-6">
                    <li>Configured LAN/WAN and managed network devices for optimal performance.</li>
                    <li>Implemented network security protocols and disaster recovery plans.</li>
                </ul>
                <p class="mt-2"><strong>ICT Support Intern</strong> - East African School of Aviation, Oct 2018 - Jan 2019</p>
                <ul class="list-disc ml-6">
                    <li>Troubleshot hardware/software issues and conducted system backups.</li>
                    <li>Supported network monitoring and software updates.</li>
                </ul>
                <p class="mt-2"><strong>ICT Support</strong> - Kenya Civil Aviation Authority, April 2018 - July 2018</p>
                <ul class="list-disc ml-6">
                    <li>Provided IT help desk support and managed user accounts in Active Directory.</li>
                    <li>Performed system upgrades and data backups.</li>
                </ul>
            </div>
            <div>
                <h3 class="text-2xl font-semibold">Certifications</h3>
                <ul class="list-disc ml-6">
                    <li>Microsoft Certified: Security, Compliance, and Identity Fundamentals - May 2025</li>
                    <li>Artificial Intelligence Fundamentals with Capstone Project, IBM - April 2025</li>
                    <li>OPSWAT Introduction to Critical Infrastructure Protection - March 2025</li>
                    <li>PWC Switzerland Power BI Job Simulation on Forage - March 2025</li>
                    <li>ICT Authority Cybersecurity and Emerging Technologies Awareness Training - Feb 2025</li>
                    <li>Python Essentials 1 - Jan 2025</li>
                    <li>Introduction to Cyber Security - Nov 2024</li>
                    <li>Cisco Certified Network Associate (Routing and Switching) (Merit) - 2019</li>
                </ul>
            </div>
            <div>
                <h3 class="text-2xl font-semibold">Technical Skills</h3>
                <ul class="list-disc ml-6">
                    <li><strong>Operating Systems:</strong> Windows, Linux</li>
                    <li><strong>Security Operations:</strong> Microsoft Defender for Cloud, Azure Security Center, Sentinel</li>
                    <li><strong>Cybersecurity Frameworks:</strong> SIEM, Wireshark, Nessus, Kali Linux, Intrusion Detection, Firewalls</li>
                    <li><strong>Virtualization:</strong> VMware, Hyper-V</li>
                    <li><strong>Compliance & Standards:</strong> ISO 27001, NIST, CIS Benchmarks, GDPR</li>
                    <li><strong>Cloud Technologies:</strong> Oracle Cloud Infrastructure, Azure, AWS, Google</li>
                    <li><strong>Programming:</strong> Java, C#, CSS, PHP, MATLAB, Python, Angular, jQuery, React</li>
                    <li><strong>Software:</strong> Power BI, Tableau, MS Office, Visual Studio, Photoshop, cPanel</li>
                    <li><strong>Databases:</strong> MySQL, MongoDB, Firebase</li>
                    <li><strong>Network Security:</strong> Azure Firewall, NSGs, IDS/IPS, DDoS Protection</li>
                </ul>
            </div>
            <div>
                <h3 class="text-2xl font-semibold">Languages</h3>
                <ul class="list-disc ml-6">
                    <li>English (Fluent)</li>
                    <li>Kiswahili (Fluent)</li>
                    <li>French (Intermediate)</li>
                </ul>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="py-16 bg-white">
        <h2 class="text-3xl font-bold mb-8 text-center">Projects</h2>
        <div class="max-w-4xl mx-auto px-4 grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
            <div class="border rounded-lg p-6 shadow hover:shadow-lg">
                <h3 class="text-xl font-semibold">Cloud Security Demo Lab</h3>
                <p class="mt-2">Built a secure Azure environment with virtual machines, network security groups, and monitoring tools. Implemented Conditional Access and MFA policies.</p>
                <p class="mt-2"><strong>Technologies:</strong> Azure, VMs, NSGs, Conditional Access, MFA</p>
                <a href="https://github.com/lusegasharon/cloud-security-lab" class="text-blue-600 hover:underline">GitHub</a>
            </div>
            <div class="border rounded-lg p-6 shadow hover:shadow-lg">
                <h3 class="text-xl font-semibold">Network Monitoring Dashboard</h3>
                <p class="mt-2">Developed a dashboard to visualize network traffic and detect anomalies using Power BI and Python.</p>
                <p class="mt-2"><strong>Technologies:</strong> Power BI, Python, MySQL</p>
                <a href="https://github.com/lusegasharon/network-dashboard" class="text-blue-600 hover:underline">GitHub</a>
            </div>
            <div class="border rounded-lg p-6 shadow hover:shadow-lg">
                <h3 class="text-xl font-semibold">Inventory Management System</h3>
                <p class="mt-2">Created a web-based system for tracking ICT equipment using React and Firebase.</p>
                <p class="mt-2"><strong>Technologies:</strong> React, Firebase, JavaScript</p>
                <a href="https://github.com/lusegasharon/inventory-system" class="text-blue-600 hover:underline">GitHub</a>
            </div>
        </div>
    </section>

    <!-- Lab Challenges Section -->
    <section id="challenges" class="py-16 max-w-4xl mx-auto px-4">
        <h2 class="text-3xl font-bold mb-8 text-center">Lab Challenges</h2>
        <div class="space-y-12">
            <div>
                <h3 class="text-xl font-semibold">Microsoft Entra ID User Settings</h3>
                <p><strong>Problem Statement:</strong> Configure user settings in Microsoft Entra ID to manage identities and assign licenses.</p>
                <p><strong>Approach:</strong> Accessed the Microsoft Entra admin center, created a new user, set usage location and sign-in status, and assigned Microsoft 365 licenses.</p>
                <p><strong>Tools Used:</strong> Microsoft Entra Admin Center, Microsoft 365</p>
                <p><strong>Key Lessons:</strong> Learned the importance of proper user configuration for secure identity management and license allocation.</p>
                <img src="https://via.placeholder.com/600x300?text=Entra+ID+User+Settings+Screenshot" alt="Entra ID User Settings Screenshot" class="mt-4 rounded shadow">
            </div>
            <div>
                <h3 class="text-xl font-semibold">Microsoft Entra Self-Service Password Reset</h3>
                <p><strong>Problem Statement:</strong> Enable and test self-service password reset (SSPR) for users in Microsoft Entra ID.</p>
                <p><strong>Approach:</strong> Enabled SSPR, added a user to the SSPR security group, registered the user for SSPR, performed a password reset, and reviewed audit logs to verify activity tracking.</p>
                <p><strong>Tools Used:</strong> Microsoft Entra Admin Center, Azure Portal</p>
                <p><strong>Key Lessons:</strong> Understood the configuration of SSPR and the role of audit logs in monitoring user activities.</p>
                <img src="https://via.placeholder.com/600x300?text=SSPR+Screenshot" alt="SSPR Screenshot" class="mt-4 rounded shadow">
            </div>
            <div>
                <h3 class="text-xl font-semibold">Microsoft Entra Conditional Access</h3>
                <p><strong>Problem Statement:</strong> Implement a Conditional Access policy to enforce MFA for Microsoft Admin portal access.</p>
                <p><strong>Approach:</strong> Created a Conditional Access policy in Microsoft Entra, enforced MFA, registered a user for MFA, and verified policy enforcement during sign-in.</p>
                <p><strong>Tools Used:</strong> Microsoft Entra Admin Center, Azure Portal</p>
                <p><strong>Key Lessons:</strong> Gained expertise in configuring MFA policies to enhance security for sensitive applications.</p>
                <img src="https://via.placeholder.com/600x300?text=Conditional+Access+Screenshot" alt="Conditional Access Screenshot" class="mt-4 rounded shadow">
            </div>
            <div>
                <h3 class="text-xl font-semibold">Microsoft Entra Privileged Identity Management</h3>
                <p><strong>Problem Statement:</strong> Manage privileged roles with time-bound access using Microsoft Entra PIM.</p>
                <p><strong>Approach:</strong> Assigned the User Administrator role to a user with time-bound activation, activated the role, and added a user to a group to test functionality.</p>
                <p><strong>Tools Used:</strong> Microsoft Entra Admin Center, Azure Portal</p>
                <p><strong>Key Lessons:</strong> Learned the importance of just-in-time access and PIM for secure role management.</p>
                <img src="https://via.placeholder.com/600x300?text=PIM+Screenshot" alt="PIM Screenshot" class="mt-4 rounded shadow">
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-16 bg-gray-200">
        <h2 class="text-3xl font-bold mb-8 text-center">Contact</h2>
        <div class="max-w-4xl mx-auto px-4 text-center">
            <p><strong>Email:</strong> <a href="mailto:lusegasharon@gmail.com" class="text-blue-600 hover:underline">lusegasharon@gmail.com</a></p>
            <p><strong>LinkedIn:</strong> <a href="https://linkedin.com/in/lusegasharon" class="text-blue-600 hover:underline">linkedin.com/in/lusegasharon</a></p>
            <p><strong>GitHub:</strong> <a href="https://github.com/lusegasharon" class="text-blue-600 hover:underline">github.com/lusegasharon</a></p>
            <p><strong>Phone:</strong> +254703109289</p>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-4 text-center">
        <p>© 2025 Sharon Mwanje Lusega. All rights reserved.</p>
    </footer>
</body>
</html>
