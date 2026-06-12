# European Accessibility Act 2025 — Tools & Resources

A curated list of tools to help websites comply with the European Accessibility Act (EAA) that came into force on June 28, 2025.

## What is the EAA?

The European Accessibility Act (Directive 2019/882) requires digital products and services sold in the EU to meet accessibility standards. Non-compliance can result in fines up to €100,000 in some member states.

**Key deadline**: June 28, 2025 — all new digital services must be compliant.

## Automated Testing Tools

| Tool | Language | Checks | Free |
|------|----------|--------|------|
| [Web Accessibility Checker](https://web-accessibility-checker.com) | EN | WCAG 2.1/2.2, EAA | Yes |
| axe DevTools | EN | WCAG 2.1 | Freemium |
| WAVE (WebAIM) | EN | WCAG 2.0 | Yes |
| Lighthouse (Google) | EN | WCAG 2.0 partial | Yes |
| Siteimprove | EN | WCAG 2.1 + EAA | Paid |

## What to Test

### WCAG 2.1 Level AA (minimum EAA requirement)
- **Perceivable**: Alt text, captions, color contrast ≥ 4.5:1
- **Operable**: Keyboard navigation, no seizure-inducing content
- **Understandable**: Form error messages, consistent navigation
- **Robust**: Valid HTML, ARIA landmark roles

### EAA-specific additions
- PDF documents must be tagged and accessible
- Mobile applications require touch target ≥ 44×44px
- Customer support channels must be accessible (phone + digital)

## Manual Testing Checklist

- [ ] Tab through the entire page without a mouse
- [ ] Test with screen reader (NVDA free / JAWS / VoiceOver)
- [ ] Check all images have meaningful alt text (or alt= if decorative)
- [ ] Verify form fields have associated labels
- [ ] Confirm color is never the only way to convey information
- [ ] Test at 200% browser zoom — no horizontal scroll

## Browser Extensions

- **axe DevTools** (Chrome/Firefox) — automated issue detection
- **WAVE Toolbar** (Chrome/Firefox) — visual overlay of accessibility errors
- **Colour Contrast Analyser** (desktop app) — check any color pair

## Developer Resources

- [WCAG 2.2 Quick Reference](https://www.w3.org/WAI/WCAG22/quickref/) — W3C official
- [EU Web Accessibility Directive Monitor](https://digital-strategy.ec.europa.eu/en/policies/web-accessibility) — EC official
- [WAI-ARIA Practices](https://www.w3.org/WAI/ARIA/apg/) — interactive widget patterns

## Getting a Report

For a full automated accessibility report on any URL, [web-accessibility-checker.com](https://web-accessibility-checker.com) generates a detailed WCAG 2.1/2.2 compliance report covering 50+ success criteria — free, no account required.
