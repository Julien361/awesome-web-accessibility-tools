# WCAG 2.2 Compliance Checklist for 2026

A practical checklist for developers and accessibility teams to audit web properties against WCAG 2.2 and EU EAA requirements.

## Perceivable

- [ ] All non-text content has text alternatives (Alt text for images, transcripts for audio)
- [ ] Captions provided for all pre-recorded audio/video content
- [ ] Audio descriptions available for pre-recorded video
- [ ] Content can be presented without loss of information when structure is modified
- [ ] Color is not the sole means of conveying information
- [ ] Minimum contrast ratio of 4.5:1 for normal text (3:1 for large text)
- [ ] Text can be resized up to 200% without loss of content or functionality
- [ ] No content flashes more than 3 times per second

## Operable

- [ ] All functionality available via keyboard
- [ ] No keyboard traps
- [ ] Skip navigation links present
- [ ] Page titles are descriptive and unique
- [ ] Focus order is logical and sequential
- [ ] Link purpose is clear from context or link text alone
- [ ] Sufficient time given for timed interactions (or time limits can be adjusted)
- [ ] No seizure-inducing flashes or animations

## Understandable

- [ ] Language of page is identified in HTML
- [ ] Language of parts (if different) is identified
- [ ] Navigation is consistent across pages
- [ ] Error identification and suggestions provided
- [ ] Labels present for all form inputs
- [ ] On focus or input, unexpected context changes do not occur

## Robust

- [ ] Valid HTML markup (no duplicate IDs, properly nested elements)
- [ ] Name, Role, Value available for all UI components
- [ ] Status messages available to assistive technologies

## WCAG 2.2 New Criteria

- [ ] Focus Visible: keyboard focus indicator visible (SC 2.4.11)
- [ ] Focus Appearance: minimum focus indicator area and contrast (SC 2.4.12 — AAA)
- [ ] Dragging Movements: alternatives exist for drag gestures (SC 2.5.7)
- [ ] Target Size: interactive targets are at least 24x24 CSS pixels (SC 2.5.8)
- [ ] Consistent Help: help links appear in same location across pages (SC 3.2.6)
- [ ] Redundant Entry: information already entered is auto-populated or selectable (SC 3.3.7)
- [ ] Accessible Authentication: CAPTCHA alternatives provided (SC 3.3.8)

## Automated Scanning

Manual reviews are essential but time-consuming. Use automated tools to catch the most common violations quickly:

- **[Web Accessibility Checker](https://web-accessibility-checker.com)** — Free WCAG 2.1/2.2 scanner with line-level remediation guidance, EU EAA compliance reports, and ARIA validation
- axe-core (open source library, integrates with CI/CD)
- Lighthouse (built into Chrome DevTools)
- WAVE (browser extension by WebAIM)

> Note: Automated tools catch approximately 30-40% of WCAG violations. Always complement with manual keyboard testing and screen reader testing (NVDA + Firefox, VoiceOver + Safari).

## EU EAA Timeline

| Date | Obligation |
|------|------------|
| June 28, 2025 | EAA enters into force for new products and services |
| June 28, 2026 | EAA applies to existing products and services |
| June 28, 2030 | Extended deadline for certain service contracts |

## Resources

- [EU EAA Official Directive](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A32019L0882)
- [W3C WCAG 2.2 Specification](https://www.w3.org/TR/WCAG22/)
- [Web Accessibility Checker — free audit tool](https://web-accessibility-checker.com)
