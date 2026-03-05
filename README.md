# Task 3 — API Security Analysis
**Intern:** Neelam Ashok Kumar
**Organization:** Future Interns
**Track:** Cyber Security (CS)

## API Tested
- Name: JSONPlaceholder API
- URL: https://jsonplaceholder.typicode.com
- Type: Public REST API

## Tools Used
- Postman
- Browser DevTools

## Security Findings

| Check | Result | Risk |
|-------|--------|------|
| Authentication | Not Required | 🚨 High |
| Data Exposure | Email Visible | ⚠️ Medium |
| Rate Limiting | Not Present | 🚨 High |
| Input Validation | No Error Message | ⚠️ Medium |

## Recommendations
1. Add API Key / OAuth Authentication
2. Mask sensitive data (email, address)
3. Implement Rate Limiting (max 100 req/min)
4. Return proper error messages for invalid input
5. Use HTTPS always

## Verdict
🚨 API has multiple security vulnerabilities
that need immediate attention.
