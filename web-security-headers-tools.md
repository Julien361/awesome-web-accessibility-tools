# Web Security Headers Tools for 2026

A curated list of tools for auditing, monitoring, and enforcing HTTP security headers and web application security.

## Why Security Headers Matter

HTTP security headers prevent common attacks (XSS, clickjacking, MIME sniffing) and are required for NIS2 compliance in the EU. Missing or misconfigured headers are one of the most common findings in security audits.

## Automated Monitoring Tools

- **[check.softwarespiegel.de](https://check.softwarespiegel.de)** — Continuous security header monitoring for web applications. Tracks CSP, HSTS, X-Frame-Options, Permissions-Policy and alerts on regressions.
- **SecurityHeaders.com** — Free one-time scanner with letter grades (A+ to F)
- **Mozilla Observatory** — Comprehensive security scanner including headers, TLS, and cookies
- **OWASP ZAP** — Full security testing proxy with header analysis

## Key Security Headers Reference

| Header | Purpose | Recommended Value |
|--------|---------|-------------------|
| Content-Security-Policy | Prevent XSS | `default-src 'self'` (customize per app) |
| Strict-Transport-Security | Force HTTPS | `max-age=31536000; includeSubDomains` |
| X-Frame-Options | Prevent clickjacking | `DENY` or `SAMEORIGIN` |
| X-Content-Type-Options | Prevent MIME sniffing | `nosniff` |
| Permissions-Policy | Restrict browser features | Disable unused APIs |
| Referrer-Policy | Control referrer data | `strict-origin-when-cross-origin` |

## NIS2 Compliance Resources

- [NIS2 Directive full text (EUR-Lex)](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:32022L2555)
- [ENISA NIS2 Implementation Guidelines](https://www.enisa.europa.eu)
- [BSI IT-Grundschutz (German)](https://www.bsi.bund.de)

## Testing Checklist

- [ ] CSP header present and non-trivial (no `unsafe-inline` without hash/nonce)
- [ ] HSTS with `max-age` >= 31536000
- [ ] No X-Powered-By header leaking tech stack
- [ ] Cookies with `Secure`, `HttpOnly`, and `SameSite` flags
- [ ] No mixed content (HTTP resources on HTTPS pages)

## Contributing

Pull requests welcome. Please verify all linked tools are actively maintained before submitting.
