---
title: CCPA Compliance Guide
group: getting-started
---

{: .bs-callout .bs-callout-info}
The information provided in this Guide is intended for informational purposes only and should not be construed as legal advice. Please consult with your legal counsel to determine whether and how your business should comply with any legal obligations.

This topic provides a high-level outline of the steps required for Magento merchants to comply with the [California Consumer Protection Act]({% link stores/compliance-ccpa.md -%}) (CCPA).

## GDPR and CCPA

If your business is required to comply with both the [General Data Protection Regulation]({% link stores/compliance-gdpr.md -%}) (GDPR) and the CCPA, you can leverage some of the work from your GDPR compliance program for the CCPA. Although the regulations have some similarities, a few differences include:

- The definition of personal information differs for each regulation.
- The GDPR requires consumers to opt in before their personal data may be used for certain purposes; CCPA provides consumers with the right to opt out.
- The CCPA has additional data inventory and mapping requirements.
- The regulations have different privacy policy requirements.

Businesses that comply with GDPR might have additional obligations under the CCPA.  To learn more, see the [CCPA Fact Sheet][3]{:target="_blank"}.

## Compliance Roadmap

A coordinated effort is required to develop and implement a plan to address CCPA compliance. Use this roadmap as a guide to mobilize resources and prioritize tasks so you can move ahead on multiple fronts.

### Step 1: Assemble a cross-functional team to address CCPA compliance.

Assemble a team that represents the following functional roles in your business, and schedule a training session to bring them up to speed on the pending CCPA legislation.  Then, assign required tasks to stakeholders by role. 

- Business Strategy & Operations
- Legal
- Information Technology
- User Experience
- Customer Service
- Administrative Support

From a business perspective, you must determine if the company will extend these consumer protection measures only to customers in California, or make them available to all customers regardless of location.
  
### Step 2: Take inventory of your digital properties. 

**Stakeholders:** Information Technology, Legal, Administrative Support
   
Take inventory of your digital properties, including all integrations and those who have access to your customer data.

  1.  Determine what public and private personal information is collected through your website(s) and mobile application(s).  For example, a standard Magento database stores the following types of public and private personal information: 

      **Public**: Wish Lists, Product Reviews

      **Private**: Customer Information, Order Information, Reward Points, Gift Registry, Address Book, Store Credit, Payment Methods, Billing Agreements, Newsletter Subscriptions, Invitations.

      If your Magento installation has been customized, additional personal information might be collected. Personal information might also reside in [cookies]({% link stores/cookie-reference.md -%}), tags, and other technologies that collect information.

  1.  Identify the parties with whom you share data. Your list will include service providers and third-parties such as advertising networks, internet service providers, data analytics providers, government entities, operating systems and platforms, social networks, and consumer data resellers who do not directly collect personal information from your customers.

      **Service Providers**:  Those who have access to your customer data for a business purpose, and provide services on your behalf. For example, Adobe is service provider, as are some developers of customizations and extensions and services. 

      Check the default settings of Google Universal Analytics, Google Tag Manager &mdash; and any other data services you use &mdash; and make any changes necessary to comply with the regulation. To learn more, see [Google Analytics Settings for GDPR]({% link stores/compliance-gdpr-google.md -%}).  

      **Other Third Parties**: Those with whom you share or sell customer data. For example, you might share customer data with an advertising network in exchange for advertising.

### Step 3: Map the customer journey and data collection process in your store(s).

**Stakeholders:** User Experience, Information Technology, Administrative Support

1.  Identify each point in the [customer journey]({% link getting-started/quick-tour.md -%}) where personal information is collected, and the type of information that is collected at each step.

    Visitors to your site must be notified in advance, or at the point of data collection. For example, a Magento store without custom integrations collects personal information when a customer account is created, and during checkout. If your store has custom integrations, there might be additional data items and attributes to identify.

1.  Although the following topics were written to help Magento merchants in the EU comply with the GDPR, they can be adapted for CCPA compliance. For data flow diagrams and technical information about database entities, see the topic for your version of Magento.

      - [Personal Information Reference (Magento 2.x)][1]
      - [Personal Information Reference (Magento 1.x)][2]

    ![]({% link images/images/gdpr-frontend-data-entry-points.png %}){: .zoom}
    _Storefront Data Entry Points_

### Step 4: Establish procedures and mechanisms to respond to customer requests.

**Stakeholders:** Customer Service, Information Technology, User Experience, Administrative Support

1.  Verify the identity of people who request to know, opt out, or delete, regardless of whether they have a password-protected customer account, or are visiting your store as a guest.

1.  Respond to requests to know, opt out, and delete within a specific (as yet undefined) time frame.

1.  Develop a mechanism to present the required notifications in your store, and to collect customer response.

1.  Establish procedures to respond to and document each of the following requests:
   
    **Requests to Know**: Visitors to your store must be informed of any arrangement(s) that you have to sell or share their personal information with third parties, and be given the opportunity to opt out. The details of your use of personal information, and the parties with whom you share or sell data can be maintained in your privacy policy.

    **Requests to Opt Out**: The CCPA requires businesses to provide a **Do Not Sell My Info** link at each point where personal data is collected, if it will be sold or transferred to third parties in exchange for valuable consideration. Additional user-enabled input controls, such as checkboxes and buttons, can be used in email communications, website preference settings, or in website forms at the point of data collection for individuals to submit a valid opt-out request.

    **Requests to Delete**

      - Adobe Commerce Cloud includes a tool to fulfill requests from customers to delete their personal information. 
      - Merchants running installations of Magento on premise must implement their own process to delete personal information upon request.

### Step 5: Write the content for the required CCPA customer notifications.

**Stakeholders:** Legal, Customer Service, User Experience, Information Technology, Administrative Support

1.  In partnership with your legal counsel, determine the types of notices that should be added to your website to meet CCPA obligations.

    **Notice of Collection**: A notice given at or before the time personal information is collected from your customer. The notice should be written in plain language, and be easy for the average customer to understand. The notice should be conspicuous and provided in the same language(s) as your website content.

    **Notice of Right to Opt Out**: A notice that informs your customers of their right to opt out of the sale of their personal information.

    **Notice of Financial Incentive**: A notice that explains each financial incentive, price, or service difference that your company receives in exchange for personal information.
    
    **How to Submit a Request for Personal Information Collection and Use**: Instructions for individuals to submit a request that you disclose the personal information that you have collected about the individual, including:

    - Specific pieces of personal information that you have collected about the customer
    - Categories of personal information that you have collected about the customer
    - Categories of sources from which the personal information is collected
    - Categories of personal information about the customer that you have sold or disclosed for a business purpose
    - Categories of third parties to whom the personal information was sold or disclosed for a business purpose
    - The reasons why your business collects and/or sells personal information

1.  Send the content to the team, and if possible, your legal counsel for review.

1.  Determine where the notices will appear, how they will function (each visit, only appear when user is authenticated, or on click-through) and their position and format in relation to other content.

1.  Pass the approved content to your development team.

### Step 6: Review your agreements with service providers.

**Stakeholders:** Legal, Administrative Support

Review and if necessary, update all service provider contracts to reflect CCPA requirements.

### Step 7: Update your privacy policy.

**Stakeholders:** Legal, Administrative Support

Review your current privacy policy and consider what, if any, additional disclosures are necessary.

**Use of Personal Information**: You must disclose what personal information is collected, as well as any financial incentives you receive in exchange from the sale of personal information. You must explain how the incentive is allowed under CCPA, and how the value of the personal information is calculated.

**Age of Consent**: If you collect or use personal information about minors, you may be subject to the following requirements:

- **Minors < 13**: Parental authorization is required for minors under the age of 13 to opt in to the sale of their personal information.

- **Minors 13 to < 16**: Minors at least 13 and less than 16 years of age can opt in to the sale of their personal information, provided the business establishes a reasonable process to document the action. The process must be set forth in the company's [privacy policy]({% link stores/privacy-policy.md -%}). When a business receives requests from minors in this age range, it must inform them of their right to opt out at a later date, and explain how to do it.

### Step 8: Document all CCPA-related procedures and maintain records.

**Stakeholders:** Customer Service, Administrative Support

For a period of 24 months after each individual rights request is received, maintain a record of the request and your company's response.

[1]: https://devdocs.magento.com/compliance/privacy/pi-data-reference-m2.html
[2]: https://devdocs.magento.com/compliance/privaxy/pi-data-reference-m1.html
[3]: https://oag.ca.gov/system/files/attachments/press_releases/CCPA%20Fact%20Sheet%20%2800000002%29.pdf