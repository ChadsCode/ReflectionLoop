# ReflectionLoop

**Enterprise-grade privacy solution for PII/PHI detection and redaction**

## Overview

ReflectionLoop is a powerful, single-file HTML tool that automatically detects and redacts personally identifiable information (PII) and protected health information (PHI) from text documents. This security tool is ideal for organizations handling sensitive information including healthcare providers, financial institutions, legal firms, government agencies, and any application processing confidential data.

ReflectionLoop embodies the principle of human-in-the-loop (HITL) security, creating a deliberate pause in the workflow where users must actively review and reflect on the sensitive information they're about to share. This approach builds lasting awareness and better data handling practices across your organization.

## Features

- **Comprehensive PII/PHI Detection**: 32 pattern types with 125+ regex patterns including SSN, credit cards, medical records, addresses, and more
- **100% Offline Processing**: All detection happens locally in your browser - no servers, no data transmission
- **Auto-Clear Timer**: 5-minute countdown automatically purges sensitive data from memory
- **Inactive Session Blur**: Screen obscures after 45 seconds of inactivity for visual privacy
- **Smart Confidence Scoring**: High/medium/low ratings based on contextual keyword analysis
- **Click-to-Exclude**: Manually override detections to keep specific items from being redacted
- **Multiple Export Formats**: Word (.docx), PDF, CSV, and plain text
- **Zero Dependencies**: Pure vanilla JavaScript in a single 136KB HTML file
- **Cross-Browser Compatible**: Works on Chrome, Firefox, Edge with zero console errors
- **Mobile Responsive**: Full functionality on desktop and mobile devices

## Business & Security Value

- **Addresses Critical Security Gap**: Protects against accidental exposure of sensitive information in documents
- **Regulatory Compliance**: Supports HIPAA, GDPR, PCI-DSS, FERPA, and other privacy requirements
- **Simple Implementation**: Single HTML file requires no installation or IT support
- **Enhanced Data Awareness**: Visual feedback teaches users what constitutes sensitive information
- **Audit Trail**: Export detection reports for compliance documentation

## Quick Start

1. Download the `ReflectionLoop.html` file from this repository

2. Open the file in any modern web browser (Chrome, Firefox, Edge)

3. Use the tool:
   - Paste or upload your text
   - Click "Privacy Scan" to detect sensitive information
   - Review highlighted items (click to exclude from redaction)
   - Click "Clean Text" to redact
   - Copy or export your sanitized document

That's it! No installation, no configuration files, no dependencies.

## Detection Categories

ReflectionLoop detects sensitive information across six major categories:

| Category | Detection Types |
|----------|----------------|
| **General Business** | Names, addresses, phone numbers, emails, dates of birth, company names |
| **Finance** | Credit cards, bank accounts, IBAN, SWIFT, tax IDs, transaction IDs |
| **Healthcare** | Medical record numbers, insurance IDs, CPT codes, ICD-10, diagnoses |
| **Human Resources** | Employee IDs, compensation data, dependent IDs, benefit information |
| **Government** | Passports, driver's licenses, visas, military IDs, national IDs |
| **Digital/Miscellaneous** | IP addresses, security tokens, usernames, file paths, coordinates |

## Performance Guidelines

ReflectionLoop is optimized for various document sizes:

| Document Size | Performance | Notes |
|--------------|-------------|--------|
| Up to 10,000 words | Ideal | ~23 pages single-spaced, smooth operation |
| Up to 25,000 words | Good | ~58 pages, minor lag only during export |
| 50,000-100,000 words | Reduced | 115-230 pages, noticeable lag, use "Copy Clean" |

For documents over 25,000 words, consider splitting into sections for optimal performance.

## Deployment Options

Deploy ReflectionLoop instantly with limited IT involvement:

- **Email Attachment**: Send the HTML file directly (136KB)
- **Microsoft Teams**: Share via Files tab or chat
- **SharePoint/OneDrive**: Host internally for team access
- **USB/Thumb Drive**: Perfect for air-gapped environments
- **Internal Wiki**: Embed or link from documentation
- **No installation required**: Users simply open in their browser

## Use Cases

### Security Awareness Training
- New hire PII/PHI awareness training
- Annual security refreshers with measurable improvement tracking
- Instant visual feedback on data exposure risks

### Daily Operations
- **Customer Support**: Sanitize tickets before vendor escalation
- **Development**: Clean production data for test environments
- **Legal**: Pre-screen documents before external counsel review
- **HR**: Remove PII from reports and communications
- **Sales**: Redact sensitive details from shared proposals

### Compliance & Audit
- Pre-audit document preparation
- Third-party data sharing compliance
- FOIA response sanitization
- M&A due diligence document cleaning

## Browser Support

ReflectionLoop works on all modern browsers:

- Chrome (latest)
- Firefox (latest) 
- Edge (latest)

Mobile browsers are supported with limited button cut off due to retro design limitations.

## Technical Details

- **Language**: Vanilla JavaScript (ES6+)
- **Size**: ~136KB single HTML file
- **Lines of Code**: ~3,750
- **Dependencies**: None
- **Network Calls**: Disabled for security
- **Data Storage**: Memory only (no localStorage/cookies)

## About ReflectionLoop

The name embodies the core philosophy: professionals should remain accountable, not rely solely on automated software. ReflectionLoop creates a deliberate pause where users must:

1. **Stop**: Review what information they're about to share
2. **Think**: Consider the implications of data exposure
3. **Reflect**: Actively participate in the protection process
4. **Continue**: Proceed with confidence after review

This human-in-the-loop approach makes users active participants in security rather than passive bystanders.

## About the Author

Hi, I'm Chad Wigington, a risk, compliance, and governance professional. I hold an MBA from Indiana University's Kelley School of Business and an undergraduate degree in Risk Management.

I created ReflectionLoop to help organizations protect personally identifiable information while building security awareness. This tool represents my commitment to making privacy protection accessible to everyone.

This is my last project before focusing on time with my son during his senior year and preparing for my move to Chicago. While I won't be actively supporting the project, I wanted to ship something useful that provides a stable foundation beyond an MVP.

Connect with me on [LinkedIn](https://www.linkedin.com/in/chadwigington/)

## License

This project is available under the MIT License. See the LICENSE file for details.

Copyright (c) 2025 Chad Wigington

---

**Built with**: Notepad++, VSCodium, LibreOffice, Inkscape, and coding assistance from Anthropic

**Try it now**: Download from [GitHub](https://github.com/ChadsCode/ReflectionLoop)

**Website**: [https://www.reflectionloop.com](https://www.reflectionloop.com)

*This is a personal hobby project, not associated or endorsed by any current or future employer.