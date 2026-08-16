# Campaigns.site starter

This package is a responsive starter website with signup/login UI, dashboard, campaign management, wallet test ledger, UPI-ID display field, and admin UI.

IMPORTANT:
- This is NOT a real banking/payment/UPI/IMPS integration.
- It uses browser localStorage for demonstration/testing.
- Do not use the included password storage or localStorage authentication for production.
- For a production launch, replace authentication with a secure backend/auth provider, PostgreSQL database, server-side authorization/RLS, HTTPS, CSRF protection, rate limiting, validation, logging, and an authorised payment/UPI provider where legally permitted.

Deployment:
1. Upload the folder to a static host or connect it to GitHub/Netlify.
2. Attach your Campaigns.site custom domain through your hosting provider.
3. For production, replace js/auth.js and localStorage data with a real backend/auth service.
