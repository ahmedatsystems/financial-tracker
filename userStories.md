👤 USERSTORIES.md

Purpose: Capture the experience from the user’s point of view. Helps design intuitive features with a user-first approach.

🧍 USER ROLE: Regular User (non-technical)
🎯 GOAL: Connect Gmail, track expenses automatically
🟢 Onboarding

As a user, I want to sign in with Google securely

As a user, I want to know exactly what permissions I’m granting

As a user, I want to add one or more bank email addresses (e.g., alerts@hdfcbank.net) so the app knows which emails to scan

As a user, I want the app to start working immediately after I connect and provide bank emails

📬 Email Syncing

As a user, I want the app to scan only bank-related emails that I specified

As a user, I want to trigger a manual scan and see the result immediately

As a user, I want to know when the last automatic scan happened

💳 Transaction Tracking

As a user, I want the app to extract accurate transaction details from my emails:

Amount

Merchant

Date

Type (debit/credit)

Category

As a user, I want the app to auto-categorize my spending

As a user, I want to manually edit categories if the app makes a mistake

📊 Dashboard

As a user, I want to see a clean overview of my spending

Monthly total

Breakdown by category

Timeline of transactions

As a user, I want to search and filter my transactions

As a user, I want to export my transaction history as a CSV

⚙️ Settings & Preferences

As a user, I want to manage my bank sender email list (add/edit/remove)

As a user, I want to revoke Gmail access at any time

As a user, I want to delete all my data permanently

🔒 Security & Privacy

As a user, I want to be assured that my email data is stored and used securely

As a user, I want transparency about what data is stored and why

As a user, I want to see a privacy policy and terms before using the app

🔁 Automation

As a user, I want the app to auto-sync my emails in the background (every 6/12/24 hours)

As a user, I want to receive a notification if new transactions are found (optional)

🧑 USER ROLE: Developer/Admin

As a developer, I want to view logs of email fetches and parsing errors

As a developer, I want to test new parsing rules easily

As a developer, I want to monitor CRON job health

As a developer, I want to test the app with mock Gmail data
