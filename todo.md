📦 PROJECT NAME: BankMail Tracker
🔰 PHASE 1 – Project Setup & Gmail Integration

 Initialize monorepo or split repos (frontend, backend)

 Set up Google OAuth2 credentials (GCP Console)

 Implement Google OAuth2 login

 Store Gmail access + refresh tokens securely (encrypted in DB)

 Build Gmail message fetcher with query: from:<bank-email>

 Parse message body (extract plain text or HTML → text)

 Create Supabase/PostgreSQL instance

 Define DB schema (users, bank_addresses, transactions)

 Create API to store/retrieve bank email addresses

 Allow manual test fetch of emails via button

🧠 PHASE 2 – Transaction Parsing & AI Integration

 Write regex-based parser for common debit/credit patterns

 Create OpenAI endpoint for structured JSON extraction

 Add fallback to regex if AI fails

 Create categorization logic:

 Simple keyword → category matching

 AI-based category classifier (OpenAI)

 Implement deduplication (check source_email_id before insert)

🎨 PHASE 3 – Frontend UI & Dashboard

 Set up React app with TailwindCSS (or use Next.js + Vercel)

 Build login flow (Google auth)

 Create dashboard page

 Total expenses by month

 Pie chart: Expenses by category

 Recent transactions table

 Create settings page

 Add/remove bank email addresses

 Add manual sync trigger (Scan Now)

 Make dashboard responsive (mobile/tablet)

 Add loading, empty, and error states

🔁 PHASE 4 – Automation & Background Tasks

 Set up CRON job (Render / Supabase Edge / Fly.io)

 Periodically scan each user's bank emails

 Check for new transactions

 Notify user (optional: via UI or email) of new entries

 Log background job runs and errors

🛠️ PHASE 5 – Polish, Error Handling & Edge Cases

 Handle token expiration & refresh

 Detect invalid or mistyped bank email addresses

 Prevent duplicate entries on Gmail resend/forward

 Add pagination to transactions table

 Add filters: category, date range, amount range

 CSV export of transactions

🚀 PHASE 6 – Deployment & Release

 Deploy frontend to Vercel

 Deploy backend to Render / Fly.io

 Seed test users and transactions

 Write deployment documentation

 Create landing page (optional: with explanation, privacy policy)

🔒 PHASE 7 – Security & Privacy

 Encrypt all tokens and sensitive data in DB

 Add OAuth consent screen privacy policy

 Add Terms of Service & Privacy Policy pages

 Ensure GDPR-compliance for email data (if public)

🧪 PHASE 8 – Testing & QA

 Unit tests for regex/email parser

 Unit tests for AI function response validator

 API integration tests

 End-to-end UI test using Cypress/Playwright

 Manual smoke test before launch
