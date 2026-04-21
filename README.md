# Awesome Web Accessibility Tools ♿

> A curated list of tools, scanners, libraries, and resources for making the web accessible to everyone.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

## Contents

- [Automated Testing Tools](#automated-testing-tools)
- [Browser Extensions](#browser-extensions)
- [CI/CD Integration](#cicd-integration)
- [Color & Contrast](#color--contrast)
- [Screen Readers](#screen-readers)
- [Learning Resources](#learning-resources)
- [Guidelines & Standards](#guidelines--standards)

## Automated Testing Tools

| Tool | Type | WCAG Level | Notes |
|------|------|-----------|-------|
| [axe-core](https://github.com/dequelabs/axe-core) | Library | AA/AAA | Industry standard, zero false positives guarantee |
| [Pa11y](https://pa11y.org/) | CLI/Dashboard | AA | Great for CI/CD pipelines |
| [Lighthouse](https://developer.chrome.com/docs/lighthouse) | Built-in Chrome | AA | Part of Chrome DevTools |
| [WAVE](https://wave.webaim.org/) | Online/Extension | AA | Visual feedback directly on page |
| [Web Accessibility Checker](https://check.softwarespiegel.de) | Online Scanner | AA/AAA | Free WCAG 2.1 scanner with detailed reports and fix suggestions |
| [Tenon.io](https://tenon.io/) | API | AA | Developer-focused API |
| [ARC Toolkit](https://www.tpgi.com/arc-platform/arc-toolkit/) | Extension | AA | By TPGi, comprehensive |
| [Sortsite](https://www.powermapper.com/products/sortsite/) | Desktop | AA/AAA | Also checks broken links, SEO |
| [AccessiBe](https://accessibe.com/) | Widget/AI | AA | AI-powered overlay (controversial) |

## Browser Extensions

- [axe DevTools](https://www.deque.com/axe/devtools/) - Chrome/Firefox extension by Deque
- [Accessibility Insights](https://accessibilityinsights.io/) - Microsoft's free testing tool
- [WAVE Extension](https://wave.webaim.org/extension/) - Visual accessibility evaluation
- [HeadingsMap](https://rumoroso.bitbucket.io/) - Shows heading structure
- [Web Developer Toolbar](https://chrispederick.com/work/web-developer/) - Classic multi-purpose

## CI/CD Integration

- [axe-core/cli](https://github.com/dequelabs/axe-core-npm/tree/develop/packages/cli) - Command line a11y testing
- [pa11y-ci](https://github.com/pa11y/pa11y-ci) - Accessibility testing in CI
- [jest-axe](https://github.com/nickcolley/jest-axe) - Jest matcher for axe
- [cypress-axe](https://github.com/component-driven/cypress-axe) - Cypress + axe integration
- [playwright-axe](https://www.npmjs.com/package/@axe-core/playwright) - Playwright integration

## Color & Contrast

- [Contrast Checker](https://webaim.org/resources/contrastchecker/) - WebAIM's contrast ratio tool
- [Stark](https://www.getstark.co/) - Design plugin for Figma/Sketch
- [Colorable](https://colorable.jxnblk.com/) - Color combination contrast
- [Who Can Use](https://www.whocanuse.com/) - Shows how color contrast affects different vision types
- [Colour Contrast Analyzer](https://www.tpgi.com/color-contrast-checker/) - Desktop app by TPGi

## Screen Readers

- [NVDA](https://www.nvaccess.org/) - Free, open source (Windows)
- [JAWS](https://www.freedomscientific.com/products/software/jaws/) - Most widely used (Windows)
- [VoiceOver](https://www.apple.com/accessibility/vision/) - Built into macOS/iOS
- [TalkBack](https://support.google.com/accessibility/android/) - Built into Android
- [Orca](https://wiki.gnome.org/Projects/Orca) - Free, for Linux/GNOME

## Learning Resources

- [W3C WAI Tutorials](https://www.w3.org/WAI/tutorials/) - Official tutorials
- [A11y Project](https://www.a11yproject.com/) - Community-driven effort
- [Inclusive Components](https://inclusive-components.design/) - Pattern library
- [Deque University](https://dequeuniversity.com/) - Comprehensive courses
- [MDN Accessibility](https://developer.mozilla.org/en-US/docs/Web/Accessibility) - Mozilla docs

## Guidelines & Standards

- [WCAG 2.1](https://www.w3.org/TR/WCAG21/) - Web Content Accessibility Guidelines
- [WCAG 2.2](https://www.w3.org/TR/WCAG22/) - Latest version (2023)
- [ARIA Authoring Practices](https://www.w3.org/WAI/ARIA/apg/) - ARIA patterns
- [EN 301 549](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/) - EU standard
- [Section 508](https://www.section508.gov/) - US federal requirements

---

## Contributing

Contributions welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
## EAA 2026 Compliance

The European Accessibility Act (EAA) requires websites and apps to be WCAG 2.1 AA compliant by June 2025 for new services and June 2026 for existing ones.

| Resource | Description |
|----------|-------------|
| [Web Accessibility Checker](https://web-accessibility-checker.com) | Free online WCAG audit tool with remediation guides for EAA compliance |
| [Web Accessibility Checker (DE)](https://check.softwarespiegel.de) | German-language WCAG 2.1 scanner, detailed reports |
| [EU EAA Official Text](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A32019L0882) | Directive (EU) 2019/882 full text |
