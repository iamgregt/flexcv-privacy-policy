> **Archived.** FlexCV is retired: its work now lives in Career in gt-hub (https://github.com/iamgregt/actualinfra), the Actual Infra product.

# Privacy Policy for FlexCV Job Capture

**Effective Date: January 8, 2025**  
**Version: 1.0**

## 1. Introduction

This Privacy Policy ("Policy") describes how the FlexCV Job Capture Chrome Extension ("Extension", "we", "us", or "our") collects, uses, stores, and protects your information. By installing and using this Extension, you agree to the data practices described in this Policy.

**Data Controller Contact:**  
Gregory Taylor  
Email: greg@flexcv.ai  
Address: 1000 Park Avenue NE, Atlanta, GA 30326

## 2. Information We Collect

### 2.1 Authentication Information
- **Data Collected**: OAuth2 tokens (access tokens, ID tokens, refresh tokens) from Microsoft Azure Active Directory
- **Purpose**: To authenticate users with the FlexCV API service
- **Legal Basis**: Legitimate interest in providing the service functionality
- **Storage**: Chrome's secure session storage (ephemeral)

### 2.2 Website Content Data
- **Data Collected**: Public job posting information from Indeed.com, specifically:
  - Job title and description
  - Company name and rating
  - Location (job location, not user location)
  - Salary information (when available)
  - Job type, benefits, and requirements
  - Job posting URL
  - Timestamp of data capture
- **Purpose**: To analyze job postings for resume customization
- **Legal Basis**: User consent through explicit action (keyboard shortcut or button click)
- **Storage**: Chrome's local storage (temporary)

### 2.3 Technical Information
- **Data Collected**: Extension errors and performance metrics
- **Purpose**: To maintain and improve Extension functionality
- **Legal Basis**: Legitimate interest in service improvement
- **Storage**: Browser console only (not transmitted)

## 3. How We Use Your Information

We use collected information exclusively for:
1. Authenticating you with the FlexCV service
2. Extracting job posting data upon your explicit request
3. Transmitting extracted data to the FlexCV API for resume tailoring
4. Providing status notifications about Extension operations

**Data Minimization**: We only collect the minimum data necessary to provide our service functionality.

## 4. Data Sharing and Third Parties

### 4.1 Third-Party Services
Your data is shared only with:
- **Microsoft Azure Active Directory**: For authentication services
- **FlexCV API** (flexcvapp.azurewebsites.net): For processing job data

### 4.2 No Sale of Data
We do not sell, rent, or trade your personal information to any third parties.

### 4.3 Legal Disclosure
We may disclose information if required by law, court order, or government request.

## 5. Data Storage and Security

### 5.1 Storage Locations
- **Authentication tokens**: Browser session storage (cleared on browser close)
- **Job data**: Browser local storage (cleared after successful API submission)
- **No external servers**: We do not operate any data storage servers

### 5.2 Security Measures
- All data transmission uses HTTPS encryption
- OAuth2 with PKCE for secure authentication
- No persistent storage of sensitive data
- Automatic token expiration and refresh

### 5.3 Data Retention
- **Authentication tokens**: Duration of browser session (max 24 hours)
- **Job posting data**: Maximum 7 days or until successful submission
- **Error logs**: Browser session only

## 6. Your Rights and Controls

### 6.1 Access and Portability
You can access all locally stored data through Chrome Developer Tools.

### 6.2 Deletion
- Remove all data by uninstalling the Extension
- Clear specific data via Chrome's Clear Browsing Data feature
- Revoke authentication through Microsoft account settings

### 6.3 Opt-Out
Stop data collection at any time by:
- Disabling the Extension
- Not using the capture functionality
- Revoking permissions in Chrome settings

### 6.4 GDPR Rights (EU Residents)
- Right to access your data
- Right to rectification
- Right to erasure ("right to be forgotten")
- Right to restrict processing
- Right to data portability
- Right to object to processing

### 6.5 CCPA Rights (California Residents)
- Right to know what information is collected
- Right to delete personal information
- Right to opt-out of sale (we do not sell data)
- Right to non-discrimination

## 7. Cookies and Tracking

This Extension does not use cookies or tracking technologies. We do not collect analytics or usage statistics.

## 8. Children's Privacy

This Extension is not intended for use by children under 16. We do not knowingly collect information from children. If you believe we have collected data from a child, please contact us immediately.

## 9. International Data Transfers

Authentication data may be processed by Microsoft servers globally. By using this Extension, you consent to such transfers in accordance with this Policy.

## 10. Data Breach Notification

In the event of a data breach affecting your personal information, we will notify affected users within 72 hours via the contact information associated with your Chrome Web Store account.

## 11. Changes to This Policy

We may update this Policy periodically. Changes will be indicated by:
- Updating the "Effective Date" and version number
- Posting a notification in the Extension update notes
- For material changes, requesting renewed consent

## 12. Legal Compliance

This Extension complies with:
- Chrome Web Store Developer Program Policies
- General Data Protection Regulation (GDPR)
- California Consumer Privacy Act (CCPA)
- Other applicable data protection laws

## 13. Dispute Resolution

Any disputes relating to this Policy will be resolved through binding arbitration in accordance with the rules of the American Arbitration Association (AAA) in Georgia, United States.

## 14. Contact Information

For privacy-related inquiries or to exercise your rights:

**Email**: privacy@flexcv.ai  
**Mail**: 1000 Park Avenue NE, Apt 1604, Atlanta, GA 30326  
**Response Time**: Within 30 days

For technical support: support@flexcv.ai

## 15. Consent

By installing and using this Extension, you acknowledge that you have read, understood, and agree to this Privacy Policy.

---

**Last Reviewed**: January 8, 2025  
**Policy Version**: 1.0.0