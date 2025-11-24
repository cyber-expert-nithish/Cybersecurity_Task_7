Task 7: Browser Extension Security Analysis
Cybersecurity Internship - Task 7

Executive Summary
Conducted comprehensive security audit of browser extensions and identified *2 high-risk extensions* requiring immediate removal. Chrome's Safety Check flagged 1 extension for policy violations.

Analysis Overview

Browser: Google Chrome  
Date: [24-11-2025]  
Total Extensions Found: 7  
Suspicious Extensions: 2  
Extensions Removed: 2  
Safe Extensions Verified: 5

CRITICAL FINDINGS

Chrome Safety Check Alert
Chrome's built-in security identified:
> "Review 1 extension that may be unsafe - Chrome recommends that you remove it"

---

SUSPICIOUS EXTENSIONS IDENTIFIED & REMOVED

1. 360 Internet Protection - CRITICAL THREAT

Basic Information:
- Version: 2.1.57
- Size: < 1 MB
- Developer: Unknown (Third-party)
- Status: Disabled but installed

Security Warnings:
- Violates Chrome Web Store policy
- Not trusted by Enhanced Safe Browsing
- Installed by third-party (not user-initiated)
- Chrome actively recommends removal

Permissions Granted:
- Read and change data on all websites
- Automatically allow access on specific sites
- Can record browsing history (even in Incognito mode warning)

Risk Assessment: CRITICAL

Threats Identified:
1. Data Theft: Can intercept and modify all web traffic
2. Privacy Violation: Tracks browsing behavior
3. Policy Breach: Violates Google's security standards
4. Unauthorized Installation: Added without explicit user consent
5. Potential Malware: 360 Total Security has history of bundled software

Why It's Dangerous:
- Extensions that violate Chrome Web Store policy have been caught engaging in malicious behavior
- Can inject ads, redirect searches, or steal credentials
- Third-party installation suggests it came bundled with other software
- Can change website content before you see it

Action Taken: REMOVED

---

2. Web Saver - HIGH RISK

Basic Information:
- Version: 1.0
- Size: < 1 MB
- Developer: Unknown
- Status: Active (enabled on all sites)
- Source: Chrome Web Store

Description: 
"Send users to relative sites if the site they want is down"

Security Warnings:
- Not trusted by Enhanced Safe Browsing
- Extremely broad permissions

Permissions Granted:
- Read your browsing history
- Read and change ALL data on ALL websites
- Active on all sites
- Allowed in Incognito mode

Risk Assessment: HIGH

Threats Identified:
1. Complete Browsing Surveillance: Tracks every website visited
2. Data Manipulation: Can modify any website content
3. Privacy Breach: Works even in Incognito mode
4. Potential Redirects: "Relative sites" feature could send to malicious pages
5. Credential Theft: Can capture login information on any site

Why It's Dangerous:
- Access to "all sites" means it can read passwords, credit cards, personal messages
- Browsing history access enables detailed user profiling
- Redirect functionality could lead to phishing sites
- Incognito tracking defeats privacy protections
- Vague description hides true functionality

Action Taken: REMOVED

---

VERIFIED SAFE EXTENSIONS

3. Adobe Acrobat: PDF Edit, Convert, Sign Tools
- Publisher: Adobe Inc. (Official)
- Status: Enabled
- Assessment: SAFE
- Permissions: PDF file handling only
- Verification: Official Adobe product, legitimate use case
- Action: KEPT

4. Google Docs Offline
- Publisher: Google LLC (Official)
- Status: Enabled
- Assessment: SAFE
- Purpose: Offline document access
- Verification: Official Google extension
- Action: KEPT

5. Application Launcher For Drive (by Google)
- Publisher: Google LLC (Official)
- Status: Enabled
- Assessment: SAFE
- Purpose: Open Drive files in local applications
- Verification: Official Google extension
- Action: KEPT

6. McAfee® WebAdvisor
- Publisher: McAfee LLC (Official)
- Status: Enabled
- Assessment: SAFE (if intentionally installed)
- Purpose: Website safety ratings, phishing protection
- Note: Verify this was installed intentionally, sometimes bundled with software
- Action: KEPT (pending user verification)

7. WPS PDF - Read, Edit, Fill, Convert, and AI Chat
- Publisher: WPS Office
- Status: DISABLED
- Assessment: LEGITIMATE (when disabled)
- Purpose: PDF editing tools
- Note: Legitimate software if intentionally installed
- Action: KEPT DISABLED

---

Security Analysis

Permission Comparison Table

| Extension | Risk Level |
|-----------|------------|
| 360 Internet Protection | CRITICAL |
| Web Saver | HIGH |
| Adobe Acrobat |LOW |
| Google Docs Offline |LOW |
| Drive Launcher |LOW |
| McAfee WebAdvisor |LOW |
| WPS PDF (disabled) |LOW |

---

Actions Taken

Immediate Actions:
1. Identified 2 high-risk extensions via Chrome Safety Check
2. Documented all extension permissions before removal
3. Removed "360 Internet Protection" (policy violation)
4. Removed "Web Saver" (untrusted, excessive permissions)
5. Verified remaining 5 extensions as legitimate
6. Restarted browser to complete cleanup

Post-Removal Observations:
- Browser startup speed: [Improved/No change]
- Page load times: [Faster/Same]
- Unwanted pop-ups: [Eliminated/None before]
- Search redirects: [Fixed/Not present]

---

Key Learnings

1. Chrome Safety Check is Essential
- Built-in security tool effectively identifies policy violations
- Should be run regularly (at least monthly)
- Provides clear warnings about unsafe extensions

2. Enhanced Safe Browsing is Critical
- Extensions "not trusted" by this system should be removed immediately
- This is a strong indicator of malicious behavior or security risks

3. Source Matters
- "Added by third-party" is a major red flag
- Even Chrome Web Store extensions can be malicious
- Always verify developer authenticity

4. Permission Awareness
- "Read and change all data on websites" = full access to everything
- "Read browsing history" = complete tracking capability
- "Allow in Incognito" = defeats privacy protections

5. Bundled Software Risks
- Extensions like 360 Internet Protection often come with other software
- Always use "Custom" installation and decline additional offers
- Review extensions immediately after installing any software

---


*Security Status: ✅ **SECURED* - All malicious extensions removed, legitimate extensions verified.
