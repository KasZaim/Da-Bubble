# Security Notice

## Firebase Credentials in Git History

⚠️ **IMPORTANT SECURITY WARNING** ⚠️

This repository contains Firebase API keys and configuration data in its Git history. If you plan to use this codebase:

### Immediate Actions Required:

1. **Create new Firebase project** - Don't reuse the existing one
2. **Generate new API keys** in your Firebase Console
3. **Configure your own environment.ts** file with your new credentials
4. **Never commit environment.ts** to your repository

### For Repository Owners:

The following Firebase credentials in the Git history should be considered **compromised** and **rotated immediately**:
- API Keys starting with `AIzaSyD7uqij9ob...`
- Project ID: `dabubble-2a68b`
- All associated configuration

### Clean Repository Setup:

For a completely clean setup without sensitive data in Git history:

1. Download the latest code as ZIP (don't clone)
2. Initialize a new Git repository
3. Configure your own Firebase project
4. Start with a fresh Git history

This notice will be removed once the Git history has been properly cleaned.