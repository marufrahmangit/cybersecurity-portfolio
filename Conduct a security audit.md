# Controls and Compliance Assessment 

## Case Study

This is based on a fictional company:

Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location, which serves as their main office, a storefront, and warehouse for their products. However, Botium Toy’s online presence has grown, attracting customers in the U.S. and abroad. As a result, their information technology (IT) department is under increasing pressure to support their online market worldwide. 

The manager of the IT department has decided that an internal IT audit needs to be conducted. She expresses concerns about not having a solidified plan of action to ensure business continuity and compliance, as the business grows. She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to internally processing and accepting online payments and conducting business in the European Union (E.U.).   

The IT manager starts by implementing the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), establishing an audit scope and goals, listing assets currently managed by the IT department, and completing a risk assessment. The goal of the audit is to provide an overview of the risks and/or fines that the company might experience due to the current state of their security posture.

Your task is to review the IT manager’s scope, goals, and risk assessment report. Then, perform an internal audit by completing a controls and compliance checklist.

## Scenario
Botium Toys: Scope, Goals, and Risk Assessment Report

### Scope 

The scope of this audit is defined as the entire security program at Botium Toys. This includes their assets like employee equipment and devices, their internal network, and their systems. You will need to review the assets Botium Toys has and the controls and compliance practices they have in place.

### Goals
Assess existing assets and complete the controls and compliance checklist to determine which controls and compliance best practices need to be implemented to  improve Botium Toys’ security posture.

### Current assets
Assets managed by the IT Department include: 
* On-premises equipment for in-office business needs
* Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.
* Storefront products available for retail sale on site and online; stored in the company’s adjoining warehouse
* Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management
* Internet access
* Internal network
* Data retention and storage
* Legacy system maintenance: end-of-life systems that require human monitoring 

### Risk assessment

#### Risk description
Currently, there is inadequate management of assets. Additionally, Botium Toys does not have all of the proper controls in place and may not be fully compliant with U.S. and international regulations and standards. 

#### Control best practices
The first of the five functions of the NIST CSF is Identify. Botium Toys will need to dedicate resources to identify assets so they can appropriately manage them. Additionally, they will need to classify existing assets and determine the impact of the loss of existing assets, including systems, on business continuity.

#### Risk score
On a scale of 1 to 10, the risk score is 8, which is fairly high. This is due to a lack of controls and adherence to compliance best practices.

#### Additional comments
The potential impact from the loss of an asset is rated as medium because the IT department does not know which assets would be at risk. The risk to assets or fines from governing bodies is high because Botium Toys does not have all of the necessary controls in place and is not fully adhering to best practices related to compliance regulations that keep critical data private/secure. Review the following bullet points for specific details:

#### Additional Info 

In Cybersecurity, control types can be classified in three ways: 
1. Administrative/Managerial controls
2. Technical controls
3. Physical/Operational controls

Control types (providing defense and protecting assets) include, but are not limited to:
1. Preventative (preventing an incident from occurring in the first place)
2. Corrective (restoring an asset after an incident)
3. Detective (Determining whether an incident has occurred or is in progress)
4. Deterrent (Discouraging attacks)

## Controls Assessment Checklist

Does Botium Toys currently have this control in place? 

| Yes / No | Control | Explanation |
| :-------        |    :---:   | :---     |
| No | Least Privilege | The employees have access to customer data. This has to be changed to reduce the risk of breach. |
| No | Disaster Recovery Plan | At the moment, there is no plan for handling the disaster. Implementing this ensures business continuity. |
| Yes* | Password policies | Password policy exists but its requirements are nominal and not in line with current minimum password complexity requirements. |
| No | Separation of Duties | The employees have access to customer data. This has to be changed to reduce the risk of breach. |
| Yes | Firewall | The organization has a firewall to block traffic based on an appropriately defined set of security rules. |
| No | IDS | This would help the IT team to identify possible intrusions by the threat actors. |
| Yes | Antivirus | The antivirus software is active and regularly monitored by the IT team. |
| No | Backups | This is the same as the disaster recovery plan. They are not prepared in the case of a breach. They have to implement a backup plan, such as incremental, full, or partial. |
| No | Encryption | This would protect the confidentiality of data. |
| Yes | Storefront | Although the IT team is not responsible for the management at the storefront, however, the organization should have sufficient locks.|
| Yes | CCTV | It is working and functioning. |
| Yes | Fire detection | The organization has these. However, the team should maintain it and establish a plan on how to use it. |

`*` *has condition*

## Compliance Checklist
Does Botium Toys currently adhere to this compliance best practice? 

* Payment Card Industry Data Security Standard (PCI DSS)

| Yes/ No / ? | Best Practice | Explanation |
| :---        |    :---:   | :---     |
| No | Authorized users can access to customer's credit card. | At the moment, all employees have access to it which is a bad practice in the business.  |
| No | Credit card is stored in a secure environment. | It is not encrypted and violates the law and regulations. |
| No | Encryption is secured. | No, the encryption has not taken place yet. | 

* GDPR
  
| Yes/ No / ? | Best Practice | Explanation |
| :---        |    :---:   | :---     |
| No | EU customers are kept secure. | The organization does not apply GDPR practice. Thus, it puts them at risk of being fined by the EU government. |
| Yes | Privacy policies are maintained properly.| According to the scenario, it has been enforced by the IT Team members and other staff. |

* System and Organizations Controls 

| Yes/ No / ? | Best Practice | Explanation |
| :---        |    :---:   | :---     |
| No | User access policies are established | Employees have access to internally stored data which means the access policy has not been applied. |
| Yes | Data integrity is consistent, complete, accurate | Data integrity is in place. | 
| No | Data is available to authorized users | Currently, all the employees can access all the data. |

## Recommendations (optional)

After researching Botium Toys's security posture, the analysts agreed that the security practice is far from the expectation. It lacks protection of confidentiality of sensitive information. The following are:
1. Least privilege
2. Disaster recovery plan
3. Password policies
4. Encryption
5. Password management system

To address gaps in compliance, Botium needs to implement and establish policies that can address the following above. Botium also needs to update its assets so that additional control can be identified as soon as possible to improve its security practices.
