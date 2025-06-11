---
title: "Lab Challenges"
permalink: /labchallenges
---

# Sharon Mwanje Lusega - Lab Challenges Portfolio

This repository showcases a collection of lab challenges completed as part of the Microsoft ADC Cybersecurity Skilling Program, highlighting my expertise in cybersecurity, cloud security, and identity management. The Lab Challenges section is presented in a professional, responsive HTML format using Tailwind CSS, suitable for GitHub Pages hosting.



## index.html
Below is the HTML code for the Lab Challenges section of the portfolio. To host this on GitHub Pages, copy the content into an `index.html` file in your GitHub repository and enable GitHub Pages.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sharon Mwanje Lusega - Lab Challenges</title>
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
                    <a href="#challenges" class="text-gray-600 hover:text-blue-600">Lab Challenges</a>
                </div>
            </div>
        </div>
    </nav>

    <!-- Lab Challenges Section -->
    <section id="challenges" class="py-16 max-w-4xl mx-auto px-4 mt-16">
        <h2 class="text-3xl font-bold mb-8 text-center">Lab Challenges</h2>
        <div class="space-y-12">
            <div>
                <h3 class="text-xl font-semibold">Microsoft Entra ID User Settings</h3>
                <p><strong>Problem Statement:</strong> Configure user settings in Microsoft Entra ID to manage identities and assign licenses for secure access.</p>
                <p><strong>Approach:</strong> Accessed the Microsoft Entra Admin Center, created a new user, configured settings such as usage location and sign-in status, and assigned Microsoft 365 licenses to enable access to services.</p>
                <p><strong>Tools Used:</strong> Microsoft Entra Admin Center, Microsoft 365</p>
                <p><strong>Key Lessons:</strong> Understood the importance of accurate user configuration for secure identity management and efficient license allocation in enterprise environments.</p>
                <img src="https://via.placeholder.com/600x300?text=Entra+ID+User+Settings+Screenshot" alt="Entra ID User Settings Screenshot" class="mt-4 rounded shadow">
            </div>
            <div>
                <h3 class="text-xl font-semibold">Microsoft Entra Conditional Access</h3>
                <p><strong>Problem Statement:</strong> Implement a Conditional Access policy to enforce multi-factor authentication (MFA) for secure access to Microsoft Admin portals.</p>
                <p><strong>Approach:</strong> Created a Conditional Access policy in Microsoft Entra, configured it to require MFA for admin portal access, registered a user for MFA, and verified policy enforcement during sign-in from the user perspective.</p>
                <p><strong>Tools Used:</strong> Microsoft Entra Admin Center, Azure Portal</p>
                <p><strong>Key Lessons:</strong> Learned how Conditional Access enhances security by enforcing context-based authentication, critical for protecting sensitive applications.</p>
                <img src="https://via.placeholder.com/600x300?text=Conditional+Access+Screenshot" alt="Conditional Access Screenshot" class="mt-4 rounded shadow">
            </div>
            <div>
                <h3 class="text-xl font-semibold">Azure Network Security Groups (NSGs)</h3>
                <p><strong>Problem Statement:</strong> Configure Network Security Groups to control network traffic for a virtual machine in Azure, allowing specific access while restricting others.</p>
                <p><strong>Approach:</strong> Created an NSG in the Azure Portal, associated it with a VM's network interface, reviewed default rules, and implemented custom rules to allow inbound RDP access and block outbound Internet traffic.</p>
                <p><strong>Tools Used:</strong> Azure Portal, Network Security Groups</p>
                <p><strong>Key Lessons:</strong> Gained expertise in using NSGs to enforce precise network traffic controls, enhancing security through rule-based access management.</p>
                <img src="https://via.placeholder.com/600x300?text=NSG+Configuration+Screenshot" alt="NSG Configuration Screenshot" class="mt-4 rounded shadow">
            </div>
            <div>
                <h3 class="text-xl font-semibold">Microsoft Sentinel Configuration</h3>
                <p><strong>Problem Statement:</strong> Set up Microsoft Sentinel to enable proactive cloud security monitoring and incident response.</p>
                <p><strong>Approach:</strong> Created a Microsoft Sentinel instance, set up a Log Analytics workspace, assigned access roles, connected data sources via the Content Hub, installed the Microsoft Defender for Cloud connector, and created an analytics rule for threat detection.</p>
                <p><strong>Tools Used:</strong> Microsoft Sentinel, Azure Portal, Log Analytics</p>
                <p><strong>Key Lessons:</strong> Understood the role of Sentinel in aggregating security data and automating threat detection, critical for proactive incident response.</p>
                <img src="https://via.placeholder.com/600x300?text=Sentinel+Configuration+Screenshot" alt="Sentinel Configuration Screenshot" class="mt-4 rounded shadow">
            </div>
            <div>
                <h3 class="text-xl font-semibold">Service Endpoints and Securing Storage</h3>
                <p><strong>Problem Statement:</strong> Configure a secure Azure network architecture with service endpoints to restrict storage access to a private subnet.</p>
                <p><strong>Approach:</strong> Created a virtual network with Public and Private subnets, configured NSGs to allow RDP and block Internet access, provisioned a storage account with a file share restricted to the Private subnet, deployed VMs, and tested connectivity to confirm access controls.</p>
                <p><strong>Tools Used:</strong> Azure Portal, Network Security Groups, Azure Storage, PowerShell</p>
                <p><strong>Key Lessons:</strong> Learned how to implement subnet isolation and service endpoints to secure storage access, reinforcing network security best practices.</p>
                <img src="https://via.placeholder.com/600x300?text=Storage+Endpoint+Screenshot" alt="Storage Endpoint Screenshot" class="mt-4 rounded shadow">
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-4 text-center">
        <p>© 2025 Sharon Mwanje Lusega. All rights reserved.</p>
    </footer>
</body>
</html>
