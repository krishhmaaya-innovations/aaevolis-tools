# Privacy Policy

## Aaevolis - AI Tools Hub

**Effective Date:** November 29, 2025  
**Last Updated:** November 29, 2025  
**Version:** 1.0  
**Developer:** Krishhmaaya Innovations  
**Extension ID:** [Will be assigned after Chrome Web Store submission]

---

## 1. Introduction

Welcome to Aaevolis - AI Tools Hub ("Extension", "we", "our", or "us"). This Privacy Policy explains how we collect, use, disclose, and safeguard your information when you use our Chrome browser extension.

We are committed to protecting your personal information and your right to privacy. If you have any questions or concerns about this policy or our practices, please contact us at the information provided below.

**Please read this Privacy Policy carefully. By installing and using the Extension, you agree to the collection and use of information in accordance with this policy.**

---

## 2. Information We Collect

### 2.1 Information We DO NOT Collect

We want to be completely transparent: **Aaevolis does NOT collect any personal data.** Specifically, we do NOT collect:

| Data Type | Collected? |
|-----------|------------|
| Personal identifiers (name, email, phone, address) | ❌ NO |
| Authentication information (passwords, credentials) | ❌ NO |
| Financial information (credit card, bank details) | ❌ NO |
| Location data (GPS, IP-based location) | ❌ NO |
| Browsing history | ❌ NO |
| Search queries | ❌ NO |
| User activity on other websites | ❌ NO |
| Cookies or tracking identifiers | ❌ NO |
| Device identifiers | ❌ NO |
| Health information | ❌ NO |
| Biometric data | ❌ NO |
| Communications content | ❌ NO |

### 2.2 Information Stored Locally

The Extension stores the following data **locally on your device only** using Chrome's built-in Storage API:

| Data | Purpose | Storage Location |
|------|---------|------------------|
| Favorite tools | To show your preferred AI tools at the top | Chrome Local Storage |
| Recently used tools | To provide quick access to tools you use often | Chrome Local Storage |
| Dark mode preference | To remember your theme choice | Chrome Local Storage |
| Cached tools list | To load the extension faster | Chrome Local Storage |

**Important:** 
- This data **never leaves your device**
- This data is **not accessible** to us or any third party
- This data is **automatically deleted** when you uninstall the extension

---

## 3. How We Use Information

Since we do not collect personal information, we do not use your personal information for any purpose.

The locally stored preferences are used solely to:
- ✅ Display your favorite AI tools at the top of the list
- ✅ Show your recently accessed tools for convenience
- ✅ Apply your preferred theme (light/dark mode)
- ✅ Load the tools list faster from cache

---

## 4. Chrome Extension Permissions

Our Extension requires the following permissions, each with a specific, limited purpose:

### 4.1 "tabs" Permission

| Purpose | Justification |
|---------|---------------|
| Open AI tool websites | When you click on an AI tool, we need this permission to open the website in a new browser tab |

**What we DON'T do with this permission:**
- ❌ We do NOT read your browsing history
- ❌ We do NOT track which websites you visit
- ❌ We do NOT access content on any webpage
- ❌ We do NOT monitor your tabs

### 4.2 "storage" Permission

| Purpose | Justification |
|---------|---------------|
| Save preferences locally | To store your favorites, recently used tools, and theme preference on your device |

**What we DON'T do with this permission:**
- ❌ We do NOT sync data to external servers
- ❌ We do NOT share stored data with anyone
- ❌ We do NOT access data from other extensions

### 4.3 "host_permissions" for GitHub

| Permission | Purpose |
|------------|---------|
| `https://raw.githubusercontent.com/*` | To fetch the list of AI tools from our public GitHub repository |

**What this means:**
- ✅ We fetch a simple JSON file containing AI tool names and URLs
- ❌ No user data is sent in this request
- ❌ No tracking or analytics involved

---

## 5. Third-Party Services

### 5.1 GitHub (Raw Content)

We fetch the list of AI tools from:
```
https://raw.githubusercontent.com/krishhmaaya-innovations/aaevolis-tools/main/tools.json
```

**Data flow:**
- **Sent to GitHub:** Only a standard HTTP GET request (no user data)
- **Received from GitHub:** A JSON file with AI tool names and URLs
- **GitHub's Privacy Policy:** https://docs.github.com/en/site-policy/privacy-policies/github-privacy-statement

### 5.2 Favicon Services

To display tool icons, we use:
- DuckDuckGo Icons: `https://icons.duckduckgo.com/ip3/{domain}.ico`
- Google Favicons (fallback): `https://www.google.com/s2/favicons?domain={domain}`

**These services only receive the domain name of AI tools (e.g., "openai.com"), not any user data.**

### 5.3 AI Tool Websites

When you click on a tool, it opens in a new tab. Each AI tool has its own privacy policy:

| Tool | Privacy Policy |
|------|----------------|
| ChatGPT | https://openai.com/privacy |
| Claude | https://www.anthropic.com/privacy |
| Gemini | https://policies.google.com/privacy |
| Others | Check each tool's website |

**We are not responsible for the privacy practices of these third-party websites.**

---

## 6. Data Sharing and Disclosure

### We DO NOT:

- ❌ Sell your data to anyone
- ❌ Share your data with advertisers
- ❌ Share your data with analytics companies
- ❌ Share your data with data brokers
- ❌ Share your data with any third parties
- ❌ Use your data for marketing purposes
- ❌ Use your data for profiling

### We MAY disclose information if:

- Required by law (subpoena, court order)
- Necessary to protect our legal rights
- Required to comply with legal process

**However, since we don't collect any data, we have nothing to disclose.**

---

## 7. Data Security

### 7.1 Local Storage Security

All data is stored using Chrome's built-in Storage API which provides:
- ✅ Encryption at rest by Chrome
- ✅ Isolation from other extensions
- ✅ Isolation from websites
- ✅ Automatic cleanup on uninstall

### 7.2 Network Security

- ✅ All external requests use HTTPS (encrypted)
- ✅ No sensitive data is transmitted
- ✅ No authentication tokens stored

### 7.3 Code Security

- ✅ No remote code execution
- ✅ No eval() or dynamic code
- ✅ Content Security Policy enforced
- ✅ Manifest V3 compliant (latest security standards)

---

## 8. Data Retention

| Data Type | Retention Period |
|-----------|------------------|
| Favorites | Until you remove them or uninstall |
| Recently used | Until you uninstall (max 5 items) |
| Theme preference | Until you uninstall |
| Cached tools | 24 hours, then refreshed |

**All data is automatically deleted when you uninstall the extension.**

---

## 9. Your Rights and Choices

### 9.1 Access Your Data

You can view stored data:
1. Right-click the extension icon
2. Click "Inspect popup"
3. Go to "Application" → "Local Storage"

### 9.2 Delete Your Data

**Option 1:** Clear from within the extension
- Your favorites and recent tools can be removed individually

**Option 2:** Uninstall the extension
- All data is automatically deleted

**Option 3:** Clear browser data
- Chrome Settings → Privacy → Clear browsing data

### 9.3 Opt-Out

Since we don't collect data, there's nothing to opt out of. However, you can:
- Disable the extension anytime
- Uninstall the extension anytime

---

## 10. Children's Privacy

### 10.1 COPPA Compliance

Our Extension does not:
- Target children under 13
- Knowingly collect information from children under 13
- Contain content inappropriate for children

### 10.2 Age Requirement

The Extension is intended for general audiences. There is no age restriction, but parental guidance is recommended for children.

---

## 11. International Users

### 11.1 GDPR Compliance (European Union)

For users in the EU:
- **Legal Basis:** Legitimate interest (providing the service you requested)
- **Data Controller:** Krishhmaaya Innovations
- **Data Collected:** None (only local storage)
- **Your Rights:** Access, rectification, erasure, portability, restriction, objection
- **No Cross-Border Transfer:** Data stays on your device

### 11.2 CCPA Compliance (California)

For California residents:
- **Categories of PI Collected:** None
- **Sale of PI:** We do not sell personal information
- **Right to Know:** We collect no data
- **Right to Delete:** Uninstall the extension
- **Non-Discrimination:** We treat all users equally

### 11.3 Other Jurisdictions

This extension complies with privacy laws worldwide by simply not collecting any personal data.

---

## 12. Updates to This Policy

### 12.1 Notification of Changes

We may update this Privacy Policy from time to time. When we do:
- The "Last Updated" date will change
- Significant changes will be noted in extension updates
- Continued use constitutes acceptance

### 12.2 Version History

| Version | Date | Changes |
|---------|------|---------|
| 1.0 | November 29, 2025 | Initial release |

---

## 13. Contact Information

If you have questions, concerns, or requests regarding this Privacy Policy:

**Developer:** Krishhmaaya Innovations

| Method | Contact |
|--------|---------|
| Email | krishhmaaya.innovations@gmail.com |

**Response Time:** We aim to respond within 48 hours.

---

## 14. Additional Disclosures

### 14.1 Affiliate Disclosure

We are NOT affiliated with any of the AI tools listed in the extension. We do not receive any commission or payment for including any tool.

### 14.2 Open Source

The tools list is publicly available at:
https://github.com/krishhmaaya-innovations/aaevolis-tools

### 14.3 Chrome Web Store

This extension is distributed through the Chrome Web Store and complies with:
- Chrome Web Store Developer Program Policies
- Chrome Extensions Quality Guidelines
- Google's Privacy Requirements for Extensions

---

## 15. Summary

| Question | Answer |
|----------|--------|
| Do you collect personal data? | **No** |
| Do you track users? | **No** |
| Do you use analytics? | **No** |
| Do you sell data? | **No** |
| Do you share data? | **No** |
| Where is data stored? | **Only on your device** |
| Is my data secure? | **Yes, encrypted by Chrome** |
| Can I delete my data? | **Yes, uninstall the extension** |

---

**© 2025 Krishhmaaya Innovations. All rights reserved.**

*This Privacy Policy was last reviewed for accuracy and compliance on November 29, 2025.*
