# **BOTIUM TOYS SECURITY AUDIT**

# Scenario

Botium Toys is a small U.S. busines that develops and sells toys. The business has a single physical location, which serves as their main office, a storefront, and warehouse for their products. However, Botium Toy's online presence has grown,, attracting customers in the U.S. and abroad. As a result, their information technology (IT) deoartment is under increasing pressure to support their online market worldwide.

The manager of the IT department has decided that an internal IT audit needs to be conducted. She's worried about maintaining compliance and business operations as the company grows without a clear plan. She believes an internal audit can help better secure the company's infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to internally processing and accepting online payments and conducting business in the European Union (E.U.).

The it manager starts by implementing the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), establishing an audit scope and goals, listing assets currently managed by the IT department, and completing a risk assessment. The goal of the audit is to provide an overview of the risks and/or fines that the company might experience due to the current state of their security posture.

# Botim Toys: Scope, Goals, and Risk Assessment Report

**Scope and Goals of the Audit**

**Scope:** The scope of this audit is defined as the entire security program at Botium Toys. This includes their assets like employee equipment and devices, their internal network, and their systems.

**Goals:** Assess existing assets and complete the controls and compliance checklist to determine which controls and co,pliance best practices hat need to be implemented to improve Botium Toy's security posture.

**Current Assets**

Assets managed by the IT Deparment include:
- On-premises equipment for in-office business needs
- Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headdsets, cables, keyboards, mice, docking stations, serveillance cameras, etc.
- Storefront products available for retail sale on site and online; stored in the company's adjoining warehouse
- Management of systems, software, and services: accounting, telecoummunication, databse, security, ecommerce, and inventory management
- Internet access
- Internal network
- Data retention and storage
- Legacy system maintenance: end-of-life systems that require human monitoring

**Risk assesment**

**Risk Description**

Currently, there is inadequate management of assets. Additionally, Botium Toys does not have all of the proper controls in place and may not be fully compliant with U.S. and international regulations and standards/

**Controls Best Practices**

The first of the five functions of the NIST CSF is identify. Botium Toys will need to dedicate resources to identify assets so they can appropriately manage them. Additionally, they will need to classify existing assets and determine the impact of the loss of existing assets, including systems, on business continuity.

**Risk Score**

On a scale of 1 to 10, the risk score is 8, which is fairly high. This is due to a lack of controls and adherence to compliance best practices.

**Additional Comments**

The potential impact from the loss of an sset is rated as medium, because the IT department does not know which assets would be at risk. The risk to assets or fines from governing bodies is high because Botium Toys does not have all of the necessary controls in place and is not fully adhering to best practices related to compliance regulations that keep critical data private/secure. Review the following bullet points for specific details:
- Currently, all Botium Toys employees have access to internally stored data and may be able to access cardholder data and customer's PII/SPII.
- Encryption is not currenly used to ensure confidentiality of customer's credit card information that is accepted, processed, transmitted, and stored locally in the company's internal databse/
- Access controls pertaining to east privilege and seperation of duties have not been implemented.
- The IT department has ensured availability and integrated controls to ensure data integrity.
- The IT department has a firewall that blocks traffic based on an appropriately defined set of security rules.
- Antivirus software is intalled and monitored regularly by the IT department.
- The IT department has not installed an intrusion detection system (IDS).
- There are no disaster recovery plans currenly in place, and the company does not have backups of critical data.
- The IT department has establilshed a plan to notify E.U. customers within 72 hours if there is a security breach. Additionally, privacy policies, procedures, and processes have been developed and are enforced among IT department members/other employees, to properly document and maintain data.
- Although a password policy exists, its requirements are nominal and not in line with current minimum password complexity requirements (e.g., at least eight characters, a combination of letters and at least one number; special characters).
- There is no centralized password management system that enforces the password policy's minimum requirements, which sometimes affects productivity when employees/vendors submit a ticket to the IT department to recover or reset a password.
- While legacy systems are monitored and maintained, there is no regular schedule in place for these tasks and intervention methods are unclear.
- The store's physical location, which includes Botium Toy's main offices, storefront, and warehouse of products, has sufficient locks, up-to-date closed-circuit tevelision (CCTV) surveillance, as well as functioning fire detection and prevention systems.

# Control Categories

**Control Categories**

Controls within cybersecurity are grouped into three main categories:
- Administrative / Managerial controls
- Technical controls
- Physical / Operational controls

**Administrative / Managerial controls** address the human component of cybersecurity. These controls include policies and procedures that define how an organization manages data and clearly defines employee responsiblities, including their role in protecting the organization. While administrative controls are typpically policy based, the enforcement of those policies may require the use of technical or physical controls.

**Technical controls** consist of solutions such as firewalls, intrusion detection system (IDS), intrusion prevention system (IPS), antivirus (AV) products, encryption, etc. Tehnical controls can be used in a number of ways to meet organizational goals and objectives.

**Physical / Operational controls** include door locks, cabinet locks, surveillance cameras, badge readers, etc. They are used to limit physical access to physical assets by unauthorized personnel.

**Control Types**

Control types include, but are not limited to:
1. Preventative
2. Corrective
3. Detective
4. Deterrent

These controsl work together to provide defense in depth and protect assets. **Preventative controls** are designed to prevent an incident from occuring in the first place. **Corrective conttols** are used to restore an asset after an incident. **Detective controls** are implemented to determine whether an incident has occured or is in progress. **Deterrent controls** are designed to discourage attacks.

Review the following charts for specific details about each type of controls and its purpose.

![image](https://github.com/jamesmchls/Botium-Toys-Security-Audit/assets/129005134/ccbdc0ab-8c11-458a-b671-1a00f6105f96)

![image](https://github.com/jamesmchls/Botium-Toys-Security-Audit/assets/129005134/3fd85041-adb0-417f-96ea-6004658f88f0)

![image](https://github.com/jamesmchls/Botium-Toys-Security-Audit/assets/129005134/c1dcf1e8-1a1c-4206-b281-fcb7264e4b3b)


**Controls Assessment Checklist**

**Administrative Controls**

![image](https://github.com/jamesmchls/Botium-Toys-Security-Audit/assets/129005134/34be24de-7b61-4cc1-9dde-39d868799469)

**Technical Controls**

![image](https://github.com/jamesmchls/Botium-Toys-Security-Audit/assets/129005134/779da02d-c157-4a42-a4b2-d3d6d3890c84)

**Physical Controls**

![image](https://github.com/jamesmchls/Botium-Toys-Security-Audit/assets/129005134/5df151d9-65d1-4f44-ac23-6d90b414a310)

**Compliance Checklist**

Botium Toys must adhere to several key standards:
1. Payment Card Industry Data Security (PCI DSS): This international standard ensures secure handling of credit card information by organizations. Botium Toys, involved in online and in-person payments and international data processing, must strictly comply to avoid severe consequences such as monetary fines, forensic audits, brand damage, and legal liabilities in case of breaches.
2. General  Data Protection Regulation (GDPR): This regulation safeguards the processing of personal data of European Union citizens, ensuring their right to privacy. Compliance is essential, especially for handling financial and personal information of EU customers, and timely breach notification within 72 hours is mandatory.
3. System and Organizations Controls (SOC Type 1, SOC Type 2): These reports assess an organization's users access policies, financial compliance, and risk levels. They evaluate confidentiality, privacy, integrity, availability, security, and data safety. Botium Toys needs to establish and maintain appropriate user access for internal and external personnel, including third-party vendors, to mitigate risks and ensure data safety. SOC 1 focuses on financial reporting controls, while SOC 2 emphasizes information security controls, including customer data protection.


# Stakeholder Memorandum

Dear Team, 

I'm sharing insights from our recent internal audit at Botium Toys, outlining the scope, objectives, critical findings, and recomendation for your review and action.

Scope:

Our audit focused on evaluating various systems, including accounting, endpoint detection, firewalls, intrusion detection system, and security information and event management (SIEM) tools. We assessed:
- Current user perimissions
- Implemented controls
- Existing procedures and protocols
- Alignment with GDPR, PCI DSS, and other compliance requirements
- Technology and asset inventory

Objectives:

Aligned with NIST CSF guidelines, our objectives aimed to:
- Enhance system compliance measures
- Strengthen controls
- Implement least privilege principles in user management
- Establish and refine policies and procedures

Critical Findings (Immediate Action Required):

Immediate attention is required for critical gaps, including:
- Least privilege and seperation of duties controls
- Disaster recovery plans
- Password, access control, and account management policies
- Intrusion detection systems (IDS)
- Encryption for secure transactions and data storage
- Backup procedures
- Password management
- Antivirus (AV) software
- Legacy system monitoring
- CCTV surveillance, locks, and fire detection

Recommendations:

To address compliance issues promptly, especially with PCI and GDPR regulations, immediate action is essential. Adhering to SOC 1 and SOC 2 guidance on user access policies and implementing least privilege principles are critical.

Disaster recovery plans and backup procedures should be prioritized for business continuity. Integrating IDS and AV software into systems will bolster threat detection capabilities.

Physical security measures, including CCTV surveillance and fire detection are crucial to safeguarding assets.

Please review these recommendations and collaborate on action plan to address these critical findings.


