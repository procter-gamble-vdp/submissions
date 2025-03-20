# Expectations for Submitting a Security Advisory
Since the standard Github Security Advisory template is designed for reporting bugs and security findings in code, we expect many Vulnerability Disclosure Program (VDP) findings will fall outside of this scope. To support this need, use the “Other” Ecosystem option and the main Description field to support the VDP requirements in the report. 

While Title and Description are the only default required fields, providing data for the optional fields may accelerate the review process.
>_NOTE: We will NOT use the temporary private fork or publish features._

All vulnerabilities reported to P&G will be Closed when:
- Reviewed and REJECTED (E.g. Not Applicable, Not Substantiated, Out-of-scope, etc.)  
  _OR_  
- Reviewed and ACCEPTED True Positive AND Confirmed Remediated.

Reference: https://docs.github.com/en/code-security/security-advisories/working-with-repository-security-advisories/about-repository-security-advisories  

![image](https://github.com/user-attachments/assets/b2a42432-cbb0-473f-9a9c-079f32a37897)

Closed submissions will remain open for comments (this is a default feature we can’t control), and they will only be re-opened by the organization admins if needed.

If a vulnerability or risk is still open after closure, we request external security researchers to open a new report.

## Submitting a Vulnerability Report as an Extenal Researcher
1. Browse to placeholder_URL to start the process and open a new security advisory using the _Report a Vulnerability_ > _Advisory Details_ form.
2. Required Fields: Title, Description
   - **Title**: Please use “Affected Target – Vulnerability” naming convention when possible.
   - **Description**: be descriptive; The more data you provide, the better we can respond.
   - In the Affected Products pane, we expect most reports will leverage the “Other” option when describing the affected ecosystem. Add additional relevant details.
   - To set expectations, an example is provided as a reference.

![image](https://github.com/user-attachments/assets/da330239-66ab-4736-8a54-e0272b7bac18)

>_NOTE: If insufficient data is provided in the Description you’ll receive a tooltip notification._

![image](https://github.com/user-attachments/assets/aeea24a4-a546-45ca-be6e-c194d7f9e27e)

3. Severity can be calculated in multiple ways.

![image](https://github.com/user-attachments/assets/0a151faa-77e9-4e0b-a722-8c5b0b311d6b)

  - **Preferred Option**: Copy and paste the vector string from the public CVE data.
    - Alternatively, you can use the drop-down menu to “Asess severity using CVSS…”, but if you copy/paste it will automatically be selected.
  - **Acceptable Options**:
    - Select a severity based on your expert knowledge. _**In this case, provide rationale for your selection in the description**_ to prevent additional back-and-forth communications.
    - Use the calculator, following the guidelines provide in the form.

![image](https://github.com/user-attachments/assets/5e0ab4d8-2cbc-4679-b4e6-b5c3ecab2ac2)

4.	Add relevant CWE data if possible, by searching or copy/paste the CWE number into the search bar. Multiple CWEs can be added this way.

![image](https://github.com/user-attachments/assets/09710fc0-35dd-450b-b465-eb303fdeff21)

5.	Post-submission, you will receive a confirmation, and our team will begin the review process.

![image](https://github.com/user-attachments/assets/8055d9f3-8edc-4042-8e4e-218045cf1d31)

>_NOTE: Any security advisories posted by a security researcher will show up at the bottom of the Security Policy section. This is only visible to the person who submitted the report.

![image](https://github.com/user-attachments/assets/089c4d97-0c48-4db3-b66d-eb7116ea2d61)

![image](https://github.com/user-attachments/assets/778ccfee-2ac3-4c92-a376-99341fe48016)

6.	Researchers can click on each submission for additional details and request feedback using _Comments_.

![image](https://github.com/user-attachments/assets/7a40562f-c518-46ea-971c-13d539161647)

>_NOTE: The Vulnerability Disclosure Program will NOT use the “temporary private fork” option”._

![image](https://github.com/user-attachments/assets/3ac7b421-e9b2-462a-a40d-eda470011e5d)

7.	After accepting the report, it will automatically move to the Draft status and the history visible to the security researcher will be updated.

![image](https://github.com/user-attachments/assets/93693acc-9b21-4497-bc3c-1d660dbae6cc)

8.	Questions, additional details and supporting evidence or attachments can be added to the report using the Comment feature.

![image](https://github.com/user-attachments/assets/7e42c20c-309e-43d1-8a13-3daa87cde5ee)

9.	The security researcher can view the status for each report submitted in the Security Tab. Clicking on the object will open the report.

![image](https://github.com/user-attachments/assets/28dbf08e-69fa-4d85-a31e-5ec88d118a79)

10.	Each report will be reviewed and categorized as:
- Reviewed and REJECTED (E.g. Not Applicable, Not Substantiated, Out-of-scope, etc.)  
  _OR_  
- Reviewed and ACCEPTED True Positive
11.	 Reviewed and REJECTED submissions will be Closed.
12.	 Reviewed and ACCEPTED True Positive submissions will remain open to allow P&G and the security researcher to communicate and collaborate.
13.	A True Positive submission will be Closed _ONLY_ after confirmed remediated by the internal P&G team.
