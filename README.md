# PhishingInvestigat

# Phishing Email Analysis – 2025-05-12

## Summary:
A suspicious email was sent from `cert@etsdc.com` with urgent financial content and a malware attachment.

## Indicators of Phishing:
- Sender domain fails SPF, DKIM, and DMARC checks
- IP address (185.222.57.74) is not authorized to send for etsdc.com
- Urgent language pressures user to confirm payments
- Attachment `invoice_10988.xz` leads to malicious `.exe`
- Malware installs and persists via startup script

## Tools Used:
- Kali Linux (`nano`, `unzip`)
- MxToolbox (header analysis)

## Conclusion:
This email is a phishing attack using spoofing, urgency, and malware to compromise the recipient.

