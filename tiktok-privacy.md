# Privacy Policy

**TheVaultDJ Upload Automation**

## Data Collection

This application collects **minimal data** and operates with strict privacy principles:

### What We Don't Collect
- ❌ Personal information (name, email, phone, address)
- ❌ Browsing history or activity logs
- ❌ Device identifiers or IP addresses (beyond API logs)
- ❌ Location data
- ❌ Payment information

### What We Store (Encrypted)
This application stores the following on a secure VPS for operational purposes only:

- **OAuth Tokens:** TikTok API refresh tokens (encrypted storage)
- **API Credentials:** Client ID and Client Secret (never shared, never logged)
- **Upload Metadata:** Video titles, descriptions, hashtags (used only for posting)

## Data Security

- 🔒 All credentials stored with file-level encryption (chmod 600)
- 🔒 No unencrypted plaintext credentials in logs or config files
- 🔒 OAuth 2.0 authentication (secure token-based access)
- 🔒 No third-party access to stored data
- 🔒 Regular security audits of credential storage

## TikTok API Privacy

This application uses the official TikTok Content Posting API, which means:
- All data transmitted to TikTok is governed by **TikTok's Privacy Policy**
- Video content posted is subject to **TikTok's Content Moderation**
- User account data remains controlled by the user and TikTok
- This application acts as a tool, not a data intermediary

## Data Deletion

You can request deletion of stored credentials at any time by:
1. Stopping the application
2. Deleting the `/root/credentials/` directory on the VPS
3. Revoking API access in your TikTok Developer settings

## Third-Party Services

This application integrates with:
- **TikTok API** - Data sent to TikTok is governed by their Privacy Policy
- **No other third parties** - No data is shared with analytics, tracking, or advertising services

## Changes to Privacy Policy

This policy may be updated at any time. Changes will be reflected with updated timestamps.

---

**Creator:** Serge (@serged67)  
**Last Updated:** April 2026  
**Questions?** Contact via GitHub: https://github.com/serged67
