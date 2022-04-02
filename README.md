# Salesforce-Email-Validation-API

This API validates emails as follows:

- It checks the ISPs and indentifies emails with invalid, inactive, parked domains or invalid accounts.
- It checks for spam traps which are put in place to identify spammers - avoiding these traps helps improve your reputation score.
- Spots domains that return valid for all emails. Skipping them will improve your open rates.
- Checks for hard bounces by sending undetectable verifications to find out whether the email address really exists and can receive email messages.
- MTA validator - Checks whether there is an email server responsible for accepting email messages? It runs advanced checks to validate MX records.
- Checks for syntax errors.
