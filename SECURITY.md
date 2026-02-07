# Security Policy

## Supported Versions

We actively support the following versions of DynaVault with security updates:

| Version | Supported          |
| ------- | ------------------ |
| 2.0.x   | :white_check_mark: |
| 1.x.x   | :x:                |

## Reporting a Vulnerability

We take security vulnerabilities seriously. If you discover a security vulnerability in DynaVault, please report it to us privately.

### How to Report

**DO NOT** create a public GitHub issue for security vulnerabilities.

Instead, please:

1. **Email us** at [nadeem.bim3@gmail.com]
2. **Include detailed information** about the vulnerability
3. **Provide steps to reproduce** if possible
4. **Include your contact information** for follow-up

### What to Include

When reporting a security vulnerability, please include:

- **Description** of the vulnerability
- **Steps to reproduce** the issue
- **Potential impact** assessment
- **Suggested fix** (if you have one)
- **Your environment details**:
  - DynaVault version
  - Operating system
  - Any relevant configuration

### Response Timeline

- **Initial response**: Within 24 hours of receiving your report
- **Vulnerability assessment**: Within 7 days
- **Fix timeline**: Critical issues within 30 days, others within 90 days
- **Public disclosure**: After fix is released and users have time to update

### Security Best Practices

When using DynaVault, we recommend:

#### For Users
- **Keep DynaVault updated** to the latest version
- **Use strong passwords** for any account-related features
- **Be cautious** when importing scripts from unknown sources
- **Regularly backup** your script library
- **Review permissions** when sharing scripts with teams

#### For Developers
- **Follow secure coding practices**
- **Validate all user inputs**
- **Use HTTPS** for any network communications
- **Keep dependencies updated**
- **Implement proper error handling**
- **Use principle of least privilege**

### Known Security Considerations

#### Local File Access
DynaVault requires access to local file systems to manage Dynamo scripts. This is by design, but users should:
- Only install DynaVault from official sources
- Be cautious when granting file system permissions
- Regularly review which directories DynaVault has access to

#### Script Execution
DynaVault does not execute Dynamo scripts directly but may:
- Read script metadata
- Generate previews
- Analyze script dependencies

### Security Updates

Security updates will be:
- **Released as patch versions** (e.g., 2.0.1, 2.0.2)
- **Documented in release notes** (without sensitive details)
- **Announced** through our official channels
- **Automatically applied** if auto-updates are enabled

### Third-Party Dependencies

We regularly audit our dependencies for security vulnerabilities:
- **Automated scanning** with tools like `npm audit`
- **Regular updates** to latest secure versions
- **Alternative libraries** evaluated when vulnerabilities are found

### Contact Information

For security-related inquiries:
- **Email**: [nadeem.bim3@gmail.com]
- **PGP Key**: Available upon request

For general support:
- **Email**: [nadeem.bim3@gmail.com]
- **GitHub Issues**: For non-security bugs and features

### Responsible Disclosure

We believe in responsible disclosure and ask that security researchers:
- **Give us reasonable time** to fix vulnerabilities before public disclosure
- **Avoid accessing or modifying** user data without permission
- **Do not perform** denial-of-service attacks
- **Only test** on your own installations
- **Respect user privacy** and data protection laws

Thank you for helping keep DynaVault and our users secure!