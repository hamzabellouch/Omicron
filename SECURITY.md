# Security Policy

## Supported Versions

The following versions of Omicron are currently supported with security and stability updates.

| Version       | Supported          |
| -------------- | ------------------ |
| 0.0.9-beta     | :white_check_mark: |
| 0.0.8-beta     | :white_check_mark: |
| 0.0.7-beta     | :white_check_mark: |
| < 0.0.7-beta   | :x:                |

---

## Reporting a Vulnerability

If you discover a security vulnerability, privacy issue, or any behavior that could negatively affect users or the application, please report it responsibly.

### Before Reporting
Please make sure that:
- The issue is reproducible
- You are using the latest supported version of Omicron
- The issue is not caused by external tools, modified builds, or unsupported environments

### How to Report
You can report vulnerabilities through:
- GitHub Issues (for non-sensitive reports)
- Private contact channels for sensitive vulnerabilities or exploit details

When reporting, please include:
- Device and Android version
- Omicron version
- Steps to reproduce the issue
- Screenshots or logs if available
- A clear explanation of the impact

### Response Policy
Security reports are reviewed as quickly as possible.  
If the issue is confirmed:
- The vulnerability will be investigated and patched
- A fix may be included in the next stable or beta release
- Credit may be given to the reporter if desired

If the report is invalid, incomplete, or not reproducible, it may be closed without action.

---

## Security Notes

Omicron uses isolated internal environments for its download engines and does not require external applications such as Termux to function.

The application currently relies on:
- `yt-dlp` for video, audio, and playlist downloading
- `gallery-dl` for image downloading

Users are strongly encouraged to keep both the application and download engines updated to receive the latest fixes and security improvements.
